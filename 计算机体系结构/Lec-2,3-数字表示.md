## 数据的编号系统

[TOC]

### 基础概念

Decimal ---- 十进制

Binary ---- 二进制

Hexadecimal ---- 十六进制

Octal number ---- 八进制数

Bit ---- 位

Byte ---- 字节

Word ---- 字（处理器一次可以处理（读/写）的位数）

### 各种进制的转换

#### 二进制 --> 十进制

#### Binary coded decimal (BCD)二进制编码的十进制

![image-20241118215339966](.\assets\image-20241118215339966.png)

#### 二进制负数的表示方式（Important ! ! !）



![image-20241119074344732](.\assets\image-20241119074344732.png)

- Sign-and-magnitude （“符号-数值”表示法）

  - 0 means positive

  - 1 means negative

    （问题是加减的时候不好使用）

- 1’s-complement（反码）

  - Flip every bit to represent negative

    （问题同样是加减的时候不好使用）

- 2’s-complement (most common)（补码）

  1. Flipping bits
  2. Add one to the 1’s complement


​	

#### Conversion between lengths

In general, pack with most-significant bits (MSB)

+18 = 0001 0010
+18 = 0000 0000 0001 0010

−18 = 1110 1110
−18 = 111111111110 1110



#### 二进制数字的计算

#### 加减法

二进制中，使用补码进行加减计算的时候，算出来的数字看开头的数字，是0就是正数，当A+(-B)中若|A|>|B|则计算出来就是正数，但这种情况都是会存在进位的情况，使得溢出，有效数字最高位变成进位之后的0？这里的溢出是需要注意的

#### 乘法

Q：为什么要取最低的有效位，如：15*15。仅使用4位表示不了



#### 二进制小数相关（Important ! ! !）

Binary Floating-Point Numbers(二进制浮点数)

![image-20250104113134322](.\assets\image-20250104113134322.png)

![image-20241119115850905](.\assets\image-20241119115850905.png)

1. **符号位（Sign bit）**：1位，表示数值的正负，0表示正数，1表示负数。

2. **指数位（Exponent bits）**：8位，用于存储指数部分。指数位使用的是偏移量（bias）表示法，对于32位浮点数，偏移量是127。实际指数值需要从存储的指数值中减去偏移量来获得。

   Bias 127 means that we use the numbers 0 to 255 in order to represent the numbers −127 to 128

   **使用的时候直接加上-127就好**

3. **尾数位（Mantissa bits）**：23位，也称为有效数字位，用于存储小数部分。在IEEE 754标准中，尾数位的第一位是隐含的，即默认为1（除非是特殊情况，如0），所以实际存储的尾数位只有23位，但表示的数值范围是24位

二进制浮点数的乘法

1. 将指数相加
2. 尾数相乘
3. 对结果进行标准化

