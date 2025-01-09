# Lec-1-Introduction

### Introduction to the Age of Computing（介绍计算机时代是什么）

这部分内容可能会出一道题，比较简单，看懂英语应该就会做

### Introduction to the Computing Profession（介绍专业计算是什么）

- 什么是专业
- 什么是计算
- 准则是什么 --- Professional responsibility in Computing



# Lec-2-Digital Technologies

### System是什么

- Technical elements
  - Hardware
  - Software
  - Networks
- Human elements
  - People
  - Process(人的活动)

这节课就是一直在讲这5个要素的发展，总体比较无聊但简单，考点琐碎，***考点全在小字部分***



# Lec-3-Software Development Processes

### Systems Development Processes

Systems Development Life Cycle ---- A Process to build Products that Deliver Value

系统开发生命周期构建交付价值的产品的流程

![image-20250109102159890](.\assets\image-20250109102159890.png)

接下来的分析全都是围绕这个图展开

1. Initiation: 

   - where from（为什么要有这个系统）
     - Kill
     - New Business processes.
     - New Business processes
   - Who from?（谁来开发这个系统）

2. Feasibility Study（可行性分析）:

   - technology perspective --- 可以实现吗，技术，风险，费用
   - business perspective --- 真的需要吗，风险，费用

3. Requirements Analysis（需求分析---要实现什么功能）:

   - People
   - Processes
   - **Functional and non functional requirements**这个可以稍稍了解下

4. System Design（系统设计）*抽象*

   - Hardware

   - Networks

   - Software

     在这三个工具上面是怎么进行具体的设计的 

5. Build（构建）*具体*

   对上面设计的实现

   在这里还提到了Types of reusable software，请仔细看下ppt

6. Implementation（部署）

   就是把程序真正的使用起来

   在这里你还要反思：需求和可行性都满足了吗

7. Maintain（维护）

   Software Support - 软件支持

   使软件不断地更新尽可能长时间地实现业务价值最大化

8. Kill（弃用）

   - 有了更好的思路
   - 开发新的系统

### The waterfall model（瀑布模型）

<div style="display: flex;">
  <div style="flex: 1; text-align: center;">
    <img src=".\assets\image-20250109111251651.png" alt="Image 1" style="width: 100%; height: auto;">
    <p>最初的瀑布模型</p>
  </div>
  <div style="flex: 1; text-align: center;">
    <img src=".\assets\image-20250109111330740.png" alt="Image 2" style="width: 100%; height: auto;">
    <p>改进版本的瀑布模型</p>
    <p>show the relationship between activities</p>  
    </div>
</div>

Avoids errors and reworking (allegedly)

### Rapid Application Development (RAD)（快速开发模型）--- iterative process

- 使用情景：
  - Small teams working fast and close to the user community building prototypes of systems and trying them out
- 使用说明
  - Produce a preliminary version of part, or a framework of all, of an information System which can be reviewed by end users 制作一个信息系统的部分或全部框架的初步版本，供最终用户审查。
  - Essentially an iterative process where users suggest modifications before further prototypes and the final information system are build. 本质上是一个迭代过程，用户在进一步的原型和最终的信息系统构建之前建议修改

- Underlying assumption:

  - Documents have value.

  - Unused software has value.

### The Unified Process（统一流程）

的好处



# Lec-4-Agile Software Development(敏捷开发)

Development process are decided through a process of **negotiation（协商）**

更多的交流

更多的交付

更少的文档

### Agile Modelling

其核心是轻量化

Travelling Light
Travelling Fast

if it is not clear that you need to keep a model then you probably don’t need it.扔掉任何不必要的东西

### Agile tools

### Kanban 

### Agile Modelling with UML

### Modelling with Use Case Diagrams

### User Stories

### eXtreme Programming（极限编程）

•New versions may be built several times per day; 新版本可能每天构建数次;

•Increments are delivered to customers **every 2 weeks**; 增量每2周交付给客户;

•All tests must be run for every build and the build is only accepted if tests run successfully.必须为每个构建运行所有测试，并且只有在测试成功运行时才接受构建。

**Ps：**

- 所有人都尽可能快地推进代码的改进
- 加班是不接受的
- 所有人都负责
- 合并之后的所有测试都要通过
- 客户是开发团队的一员
- ……

### The Scrum sprint cycle（冲刺周期）

一般是有固定的长度2-4天

起点是backlog（待办事项）

然后团队和客户一起选择在冲刺时要做的事情

The role of the Scrum master is to protect the development team from external distractions（冲刺管理员保护开发团队免受外部干扰）

**Ps:**

- Sprint一次开发迭代
- Scrum简单的所有人参加的会议
- ScrumMaster算是项目经理，用来加强各部门的合作
- **Potentially shippable product increment（潜在可交付的产品增量）**是什么意思？？？？



# Lec-5-Doing an Investigation（做调研）

这节课就是在教你怎么进行需求分析

### The Requirements Engineering process

1. **Requirements discovery：**采访获得用户需求
2. **Requirements classification and organisation：**分类到相应的组
3. **Prioritisation and negotiation：**（确定需求的优先级并解决冲突）
4. **Requirements specification：**确定下来需求进行下一次循环

### Techniques for Investigating Requirements（SQIRO）

- Sample Documents
- Questionnaires
- Interviewing
- Reading (or Research)
- Observation 

每一项调查都包含“fieldwork” 和“deskwork”

#### Observation

观察的四个等级
1) First Impressions – should quickly give you a high-level overview
2) Simple Observation
e.g. Sitting in the workplace and just watching what happens
maybe also asking simple questions “Do you get this problem a lot?”
3) Shadowing/ Tailing
Following a person as they do their job.
4) Formal Observation Methods
Gathering “metrics”, statistics based on observing behaviour, e.g. timing
actions, counting occurrences, measuring distances, estimating probabilities.
(“Time and Motion” studies)

##### Hawthorne Effect（霍桑效应）

这个短语经常被用来描述人们在知道自己被观察时表现出的正常行为的变化

#### Reading

- **The list of potential things to read is potentially endless.**：潜在的阅读材料清单可能是无穷无尽的。这意味着在任何研究或学习过程中，你可能会遇到大量的书籍、文章、报告等，以至于难以一一阅读.
- **While reading and research will help you understand the problem domain**：虽然阅读和研究可以帮助你理解问题领域。这强调了阅读和研究的重要性，通过它们可以深入了解特定领域的知识和问题.
- **it is also important to know when to stop.**：但同样重要的是要知道何时停止。这提醒我们在进行阅读和研究时，要避免陷入无休止的信息收集和分析中，因为这可能会导致效率低下和时间浪费.
- **A sensible approach is to “skim” documents quickly to assess their relevance**：一个明智的方法是快速“浏览”文件以评估它们的相关性。这里建议在面对大量阅读材料时，先进行快速浏览，以判断文件是否与你的研究或学习目标相关，从而避免在不相关或次要的内容上浪费时间.
- **and selecting only key documents for more detailed study.**：并只选择关键文件进行更详细的研究。这意味着在快速浏览后，只挑选那些最相关、最有价值的文件进行深入阅读和研究，以确保时间和精力的有效利用

#### Interviews

- 好处
- 坏处
- 问题类型
  - Closed Question
  - Open Question
  - Wide Open Question
- 采访准备
  - Prepare interviewee – time, duration, what it’s about.  
  - Maybe give them some reading or info. e.g. Work I’ve done so far.  
  - Prepare yourself – plan, a set of objectives, ensure relevant to them. 
  - Prepare your material – e.g. draft UML diagrams to discuss  
  - Explain who you are and the purpose of interview 
  - Get permission to record (if possible), video, audio or take notes 
- 应当注意
  - Stick to plan and timetable, keep control sensitively.
  - Take notes
  - Listen and encourage interviewee to expand on key points
  - Don’t put words in their mouth
- Interview Structure（采访结构）
  - Written in advance
  - Asked in order
  - At it’s most formal may be a verbally administered questionnaire
- Interviewer Personal Style（采访风格）
  - 对于采访来说
  - 对于对象来说The interviewer adapts their style, body language, tone, approach to the diametric opposite role of the Interviewee.

#### Questionnaires（问卷）

- 应当注意一个好的调查问卷需要有什么
  - branching 
  - simple and unambiguous
  - Multiple-choice
  -  date and person to whom the  questionnaire
-  Disadvantages
  - low response rates
  -  inability to use verbal and non-verbal signals
  - can not  clarify question



### Reverse Engineering Existing Systems(逆向工程现有系统)

对数据库进行拆解

提取数据库里面被封装的信息





# Lec-6-Systems Modelling

System modeling has now come to mean representing a system using some kind of graphical notation, which is now almost always based on notations in the Unified Modeling Language (UML).

系统建模现在已经意味着使用某种图形符号来表示系统，这种符号现在几乎总是基于统一建模语言（UML）中的符号。

#### 不同情况三种不同的要求

- Facilitating **discussion** about an existing or proposed system --- Incomplete and incorrect models are OK
- Documenting an **existing system** --- Models should be an accurate but need **not** be  complete
- Detailed system description  that can be used to **generate a system implementation** --- Models have to be both correct and complete

### 九种UML图？？？

![image-20250109162129082](.\assets\image-20250109162129082.png)

？？？



# Lec-7-Architecture(架构)

看课件，网络架构师是怎么工作的，职责是什么

TOGAF --- The Open Group Architectural Framework

### 架构的组成

 Architecture

-  Layers
- Components
- Sub-Components
-  Building block --- Interfaces

### 基于组件的软件架构

**个体组件** 是一个软件包、一个网络服务或一个模块，封装了一组相关功能（或数据）

### Principles of Component Design（原则）

- **purpose**（目的性）
- be internally **cohesive** and provide **external** services via a  limited interface（紧密相关）
- **Modularity**（模块化）一个系统被分解为一组内聚且松散耦合的模块的特性
- **Encapsulation**（封装性）

### Three Tier Software Architecture Presentation, Application, Data (PAD)

### The Model-View-Controller (MVC)  pattern模型-视图-控制器模型

![image-20250109174324685](.\assets\image-20250109174324685.png)

# Lec-8-Systems Design



# Lec-9-Testing



