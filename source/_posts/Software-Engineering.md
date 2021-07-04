---
title: Software_Engineering
author: Oliver
mathjax: true
abbrlink: 57655
date: 2021-06-30 19:59:06
updated: 2021-06-30 19:59:06
categories:
  - 大三下
tags:
  - 软件
permalink:
---

## Chapter 1

### 1. What is Software Engineering?

​	Software engineers use their knowledge of computers and computing to help solve problems. Software engineers use techniques, tools, procedures, and paradigms to enhance the quality of their software products. Their aim is to use efficient and productive approaches to generate effective solutions to problems.



​	软件工程师使用他们在计算机和计算方面的知识来帮助解决问题。软件工程师使用技术、工具、程序和范式来提高他们的软件产品的质量。他们的目标是使用高效和富有成效的方法来产生有效的问题解决方案。



### 2. What is good software?

1. The quality of the product.
2. The quality of the process.
3. Quality in the context of the business environment.



1. 产品的质量
2. 过程的质量
3. 商业环境中的质量



### 3. What are 9 activities in software development?

1. requirements analysis and definition
2. system design
3. program design
4. writing the programs
5. unit testing
6. integration testing
7. system testing
8. system delivery
9. maintenance



1. 需求分析和定义
2. 系统设计
3. 程序设计
4. 编写程序
5. 单元测试
6. 集成测试
7. 系统测试
8. 系统交付
9. 维护



### 4. How has software engineering changed?

1. criticality of time-to-market for commercial products
2. shifts in economics of computing: lower HW, higher development/maintenance costs
3. availability of powerful desktop computing
4. extensive local- and wide-area networking
5. availability and adoption of OO technology
6. graphical user interfaces
7. unpredictability of waterfall model of development



1. 商业产品上市时间的重要性
2. 计算机行业经济学的转变：较低的硬件成本，较高的开发/维护成本
3. 强大的桌面计算的可用性
4. 局域网和广域网的广泛应用
5. 面向对象技术的出现和应用
6. 图形化的用户界面
7. 使用瀑布模型开发的不可预测性



### 5. What is the Wasserman's discipline of software engineering?

1. abstraction
2. analysis and design methods and notations
3. user interface prototyping
4. software architecture
5. software process
6. reuse
7. measurement
8. tools and integrated environments



1. 抽象
2. 分析，设计方法和符号
3. 用户界面原型
4. 软件体系结构
5. 软件过程
6. 重用
7. 度量
8. 工具和集成环境



## Chapter 2

### 1. What are the drawbacks of the Waterfall model?

1. The model provides no guidance to managers and developers on how to handle changes to products and activities that are likely to occur during development.
2. It does not treat software as a problem-solving process. It was derived from a manufacturing view of software development. Software is a creation process, not a manufacturing process. 
3. The biggest problem with the waterfall model is that it does not reflect the way code is really developed.



1. 该模型没有为管理者和开发者提供如何处理开发过程中可能发生的产品和活动变化的指导。
2. 它没有将软件作为一个解决问题的过程。它是从软件开发的制造观点中得出的。软件是一个创造过程，而不是一个制造过程。
3. 瀑布模型的最大问题是它没有反映出代码真正的开发方式。



### 2. What are the benefits of the Incremental Model and Iterative Model?

1. Training can begin on an early release, even if some functions are missing.
2. Markets can be created early for functionality that has never before been offered.
3. Frequent releases allow developers to fix unanticipated problems globally and quickly.
4. The development team can focus on different areas of expertise with different releases.



1. 即使缺少一些功能，也可以在早期版本中开始培训。
2. 可以为以前从未提供过的功能提前创造市场。
3. 频繁的发布使开发人员能够在全球范围内快速地修复未预料到的问题。
4. 开发团队可以在不同的版本中专注于不同的专业领域。



### 3. What is incremental model?

​	The system is partitioned into subsystems by functionality. The releases are defined by beginning with one small, functional subsystem and then adding functionality with each new release.



​	增量模型将系统按功能划分为若干子系统。版本的定义从一个小的功能子系统开始，然后在每个新的版本中增加功能。



### 4. What is iterative model?

​	A full system is delivered at the very beginning and then changes the functionality of each subsystem with each new release.



​	一开始就交付一个完整的系统，然后随着每个新版本的发布而改变每个子系统的功能。



## Chapter 4

### 1. Describe the process of determining requirements.

1. Elicitation: Collecting the user's requirements.
2. Analysis: Understanding and modeling the desired behavior.
3. Specification: Documenting the behavior of the proposed software system.
4. Validation: Checking that our specification matches the user's requirements.



1. 征求意见：收集用户的需求
2. 分析：理解用户需求并对需求建模
3. 规范：记录建议的软件系统行为
4. 验证：检查我们的规范是否符合用户的需求



### 2. It is usually helpful to separate the requirements into three categories. What are these three categories? Explain why it is helpful.

1. Three categories are:
   - Requirements that absolutely must be met.
   - Requirements that are highly desirable but not necessary.
   - Requirements that are possible but could be eliminated.
2. Reasons: The analysis of requirements by category is helpful to all parties in understanding what is really needed. It is also useful when a software development project is constrained by time or resources; if the system as defined will cost too much or take too long to develop, category 3 requirements can be dropped and category 2 requirements can be analyzed for elimination or postponement.



1. 分为三类：
   - 绝对需要满足的需求
   - 想要但非必要的需求
   - 可以实现也可以不实现的需求
2. 原因：对需求进行分类有助于各方了解真正需要的是什么。它在当一个软件开发项目受到时间或资源的限制时非常有用；如果定义的系统将花费或需要太多时间来开发，第3类需求可以被放弃，第2类需求也可以考虑被取消或推迟。



### 3. What is a requirements definition document? What is a requirements specification document?

1. The requirements definition is a complete listing of everything the customer expects the proposed system to do. It represents an understanding between the customer and developer of what the customer needs or wants, and it is usually written jointly by the customer and developer.
2. The requirements specification restates the requirements definition in technical terms appropriate for the development of a system design; it is the technical counterpart to the requirements definition document, and it is written by requirements analysts.



1. 需求定义文档是一个完整的清单，列出了客户期望的系统所要做的一切。它代表了客户和开发者之间对客户需求的理解，它通常由客户和开发者共同编写。
2. 需求规格说明书用技术术语重申了需求定义，它是需求定义文档的技术对应物，由需求分析师编写。



### 4. What is a functional requirement? Give an example to explain.

​	A functional requirement describes an interaction between the system and its environment. Further, functional requirements describe how the system should behave given certain stimuli. For example, there is a button on the home page of the software, you can click on it to display the browsing history. This is a functional requirement.



​	功能性需求描述了系统和环境之间的互动。功能性需求描述了系统在特定的刺激下应该如何表现。例如，软件主页有一个按钮，点进去就能显示浏览记录，这就是功能性需求。



### 5. What is a nonfuctional requirement? Give an example to explain.

​	A nonfuctional requirement, describes a restriction on the system that limits our choices for construction a solution to the problem. For instance, we may be the system must be developed on an Linda computer. This is a nonfuctional requirement.



​	非功能性需求，描述了对系统的限制，限制了我们在面对问题的解决方案上的选择。例如，我们可能被告知系统只能部署在琳达的电脑上。这就是非功能性需求。



### 6. The following is the requirements of a system. Please draw its data flow diagram.(Back)

- 某银行计算机储蓄系统的工作过程大致如下：储户填写的存款单或取款单由业务员键入系统,如果是存款则系统记录存款人姓名、住址(或电话号码)、身份证号码、存款类型、存款日期、到期日期、利率及密码等信息，并印出存款单给储户；如果是取款而且存款时留有密码，则系统首先核对储户密码，若密码正确或存款时未留密码，则系统计算利息并印出利息清单给储户。请对以上问题画出分层数据流图。
- ![基本模型](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/Chapter5_first.png)
- ![第一级模型](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/Chapter5_second.png)
- ![第二级模型](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/Chapter5_third.png)



### 7. The following is the requirements of a system. Please draw its data flow diagram.(Airport)

- 为方便旅客, 某航空公司拟开发一个机票预订系统。旅行社把预订机票的旅客信息(姓名、性别、工作单位、身份证号码、旅行时间、旅行目的地等)输入进该系统,系统为旅客安排航班, 印出取票通知和账单, 旅客在飞机起飞的前一天凭取票通知和账单交款取票,系统校对无误即印出机票给旅客。
- ![Airport](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/airport_1.png)
- ![airport_2](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/airport_2.png)



### 8. What items should be included in the requirements definition and specification document?

1. Physical Environment
2. interfaces
3. Users and Human Factors
4. Functionality
5. Documentation
6. Data
7. Resources
8. Security
9. Quality Assurance



1. 物理环境
2. 界面
3. 用户和人类因素
4. 功能性
5. 文档
6. 数据
7. 资源
8. 安全性
9. 质量保证



### 9. Generate a transition diagram to illustrate the requirements of  an automatic bank teller machine. (ATM)

 ![ATM](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/ATM.png)



## Chapter 5

### 1. For each type of coupling, give an example of two components coupled in that way.

​	Coupling: We say that two components are highly coupled when there is a great deal of dependence between them.

1. Content coupling: Content coupling might occur when one component modifies an internal data item in another component, or when one component branches into the middle of another component.
2. Common coupling: If data are accessible from a common data store, common coupling occurs.
3. Control coupling: When on component passes parameters to control the activity of another component, we say that there is control coupling between the two.
4. Stamp coupling: When a data structure is used to pass information from one component to another, and the data structure itself is passed, there is stamp coupling between the components.
5. Data coupling: If only data are passed, the components are connected by data coupling.



​	当两个模块之间存在大量的依赖关系时，我们说它们是高度耦合的。

1. 内容耦合：当一个模块修改另一个模块的内部数据项，或者当一个模块的分支进入另一个模块的中间时，就可能发生内容耦合。
2. 公共耦合：如果数据可以从一个共同的数据存储中访问，就会发生公共耦合。
3. 控制耦合：当一个模块通过参数来控制另一个模块活动时，就会发生控制耦合。
4. 标记耦合：当一个数据结构被用来将信息从一个模块传递给另一个模块，并且数据结构本身被传递，模块之间就存在标记耦合。
5. 数据耦合：如果只有数据被传递，模块之间使通过数据耦合连接的。



### 2. For each type of cohesion, write a description of a component exhibiting that kind of cohesion.

1. Coincidental: The worst degree of cohesion, coincidental, is found in a component whose parts are unrelated to one another.
2. Logical cohesion: Logical is the next higher level of cohesion( though still not desirable), where several logically related functions or data elements are placed in the same component.
3. Temporal: Sometimes a component is used to initialize a system or a set of variables. Such a component performs several functions in sequence, but the functions are related only by the timing involved.
4. Procedurally cohesive: When functions are grouped together in a component just to ensure this order, the component is procedurally cohesive.
5. Communicationally cohesive: Modules that are designed around data sets in the way that associate certain functions because they operate on the same data set.
6. Sequential cohesion: If the output from one part of a component is input to the next part, the component has sequential cohesion.
7. Functional cohesion: Every processing element is essential to the performance of a single function, and all essential elements are contained in one component.



1. 偶然内聚：最差程度的内聚，即巧合，各个部分互不相关。
2. 逻辑内聚：下一个更高级的内聚，即几个逻辑上相关的功能或数据元素被放在同一个模块中。
3. 时间内聚：有时一个模块被用来初始化一个系统或一组变量。这样的模块依次执行几个功能，但这些功能只在涉及到的时间上有关系。
4. 过程内聚：当模块被组合在一起是为了保证执行顺序，那么这个模块就是过程内聚的。
5. 通讯内聚：围绕着数据集设计的模块，因为对同一数据集进行操作而将某些功能联系起来的方式。
6. 顺序内聚：如果一个模块的一个部分的输出是对下个部分的输入，该模块就具有顺序内聚性。
7. 功能内聚：每一个处理元素对单一功能的执行都是必不可少的，而且所有的基本元素都包含在一个模块中。



### 3. 画出下列伪码程序的程序流程图。

START 
	IF p THEN
		WHILE q DO
			f
		END DO
	ELSE
		BLOCK
			g
			n
		END  BLOCK
	END IF
STOP

- ![程序流程图](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/Chapter5.png)



### 4. What is the implicit invocation? What are advantages and disadvantages of the implicit invocation?

1. Instead of invoking a procedure directly, a component can broadcast one or more events. Other components in the system can register an interest in an event by associating a procedure with the event. When the event is announced the system itself invokes all of the procedures that have been registered for the event.

2. Advantages: 

   - This style of design is especially useful for reusing design components from other systems. Any component can be introduced into a system simply by registering it for the events of that system.
   - As the system evolves and requires upgrades, old components can be removed and new ones added easily.

3. Disadvantages：

   The biggest disadvantage of this design style is the lack of assurance that a component will respond to an event. This dependence on the context and sequence of events makes it very difficult to test the system and check for correctness.



1. 一个模块可以广播一个或多个事件，而不是直接调用一个程序。系统中的其他模块可以通过将一个过程与该事件相关联来注册该事件。当事件被宣布时，系统本身会调用所有被该事件注册的程序。
2. 优点：
   - 这种设计风格对于重复使用其他系统的设计模块非常有用。任何模块都可以被引入到一个系统中，只需为该系统的事件注册即可。
   - 随着系统的发展和需要进行升级，旧的模块可以被删除，而新的模块则很容易被添加。
3. 缺点：这种设计风格的最大缺点是不能保证一个模块会对一个事件作出反应。这种对事件背景和顺序的依赖使得测试系统和检查正确性变得非常困难。



## Chapter 6

### 1. What are major characteristics of object orientation?

1. identity
2. abstraction
3. classification
4. encapsulation
5. inheritance
6. polymorphism
7. persistence



1. 一致性
2. 抽象
3. 分类
4. 封装
5. 继承
6. 多态
7. 连续性



### 2. What is the key difference between more traditional procedural development and the OO development?

​	The across-the-process consistency is a key difference between more traditional procedural development and the OO development process. OO is a philosophy of problem and solution representation, not a software life cycle by itself.



​	跨过程的一致性是更传统的程序化开发和面向对象开发过程之间的一个关键区别。面向对象是一种问题和解决方案的表述哲学，而不是软件生命周期本身。



### 3. What is a use case?

​	A use case describes particular functionality that a system is supposed to perform or exhibit by modeling the dialog that a user, external system, or other entity will have with the system to be developed.



​	用例通过模拟用户、外部系统或其他实体与待开发系统的对话来描述系统应该执行或展示的特定功能。



### 4. Draw a use case diagram for the ATM problem.

![ATM use case](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/ATM_usecase.png)



### 5. Classify each of the following relationships as either an inheritance relationship, an aggregation relationship, or a general association.

1. Person──Student: an inheritance relationship
2. Library──Library patron: an aggregation relationship
3. Car──Driver: a general association



1. 人与学生：继承关系
2. 图书馆与图书馆赞助人：聚集关系
3. 汽车与司机：一般关联



### 6. Draw a use case diagram for the simple library problem.

![library use case](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/Library%20use%20case.png)



### 7. Draw a class diagram for the simple library problem. Suppose the classes in this problem are the library, book, copies of books, and patron.

<img src="https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/Library%20class%20diagram.png" alt="library class diagram" style="zoom:67%;" />



### 8. Suppose we have the following scenario for the simple library problem. A patron goes to the library and checks out a book. Two months later, he brings the overdue library book back to the library. Please draw a sequence diagram and a collaboration diagram for the scenario.

1. Sequence diagram:

   ![时序图](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/Library%20sequence%20diagram.png)

2. Collaboration diagram:

   ![Collaboration diagram](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/Library%20collaboration%20diagram.png)
   
   

### 9. Use the noun-in-text-description to identify the classes from the above requirement statement.

- The Royal Service Station provides three types of services to its customers: refueling, vehicle maintenance, and parking.
- Classes: service station, services, customer, refueling, vehicle maintenance, and parking.



- 类：服务站、服务、客户、加油、车辆维修、停车



### 10. Please draw a class diagram for 9.

![Royal class 1](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/Royal.png)



### 11. Use the noun-in-text-description to identify the classes from the above requirement statement.

- The station manager uses the system to control inventory. The system will warn of low inventory and automatically order new parts and fuel.
- Classes: system, manager, inventory, fuel, parts.



- 类：系统、经理、库存、燃料、零件。



### 12. Please draw a class diagram for 11.

![Royal class 2](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/Royal_second.png)



### 13. Please draw the state diagrams for the fuel and parts classes.

- fuel state diagrams:

  ![Royal state diagram](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/fuel%20state.png)

- parts state diagrams:

  ![parts](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/parts%20state.png)



### 14. Concepts and examples about aggregation, composition, association, generalization between two classes.

1. aggregation: One class is part of another class. For example, CPU is part of a computer.
2. composition: Composition is also a relationship between whole and part between classes, but the whole and part in a composition relationship have the same lifetime. For instance, a person consists of a head, arms, etcs. If this head leaves the person, then this head has no meaning.
3. association: Two classes are associated when they occur together, and when the relationship must be preserved for some period of time. For example, each order is associated with a salesperson. Until the order is complete, it is important to link the order with the salesperson.
4. generalization: The superclass generalizes the subclass. For instance, the fuel class may be a generalization of the diesel fuel class.



1. 聚集：一个类是另一个类的一部分。例如，CPU是计算机的一部分。
2. 组合：也是类之间的整体和部分的关系，但组合关系中的整体与部分具有同样的生存期。例如一个人由头、手等组成，如果这个头离开了这个人，那么这个头就没有任何意义了。
3. 关联：当两个类同时出现，且之间的关系必须保留一段时间时，就发生关联。例如，每个订单都与一个销售人员相关联。在订单完成前，将订单和销售人员联系起来是很重要的。
4. 继承：超类概括子类。例如，柴油类继承自燃料类。



## Chapter 8

### 1. What are the main software testing objectives?

1. Testing is the process of executing a program with the intent of finding errors.
2. A good test case is one with a high probability of finding an as-yet undiscovered error.
3. A successful test is one that discovers an as-yet-undiscovered error.



1. 测试是执行程序的过程，目的是为了发现错误。
2. 一个好的测试用例是能高概率发现尚未发现的错误。
3. 一个成功的测试是发现了一个尚未发现的错误。




### 2. Explain the following terms: Unit test, integration test, function test, performance test, acceptance test.

1. Unit test: Unit test verifies that the component functions properly with the types of input expected from studying the component's design. Each program component is tested on its own, isolated from the other components in the system.
2. Integration test: Integration testing is the process of verifying that the system components work together as described in the system and program design specifications. It ensures that the interfaces among the components are defined and handled properly.
3. Function test: A function test evaluates the system to determine if the functions described by the requirements specification are actually performed by the integrated system.
4. Performance test: A performance test compares the system with the remainder of these software and hardware requirements.
5. Acceptance test: An acceptance test makes certain that the system works according to customer expectations. We join the customer to perform an acceptance test, where the system is checked against the customer's requirements description.



1. 单元测试：单元测试验证了组件在设计时预设的输入类型下功能是否正常。每个程序组件都是独立测试的，与系统中的其他组件隔离。
2. 集成测试：集成测试是验证系统组件是否按照系统和程序设计规范中的描述一起工作。它确保各组件之间的接口被定义和正确处理。
3. 功能测试：对系统进行评估，以确定需求说明所描述的功能是否由集成系统实际执行。
4. 性能测试：性能测试将系统与这些软件和硬件要求的剩余部分进行比较。
5. 验收测试：验收测试可以确定系统是按照客户的期望工作的。我们与客户一起进行验收测试，根据客户的需求描述检察系统。



### 3. What are the differences between black box and white box testing?

1. Black-box testing: Knowing the specified function a product is to perform, tests  can be conducted that demonstrate each function is fully operational, at the same time searching for errors in each function.
2. White-box testing: Knowing the internal workings of all independent logic paths. White-box testing is a test case design method that uses the  control structure of the procedural design to derive test cases. 
3. The biggest difference should be that the test objects are different. White-box testing focuses on the logic of the problem code. Black-box testing focuses on the functionality that the program presents to the user.



1. 黑盒测试：知道了产品要执行的指定功能，就可以进行测试，证明每个功能是完全可执行的，同时在每个功能中寻找错误。
2. 白盒测试：知道所有独立逻辑路径的内部工作原理。白盒测试是一种测试用例设计方法，使用程序设计的控制结构来推导测试用例。
3. 最大的区别是测试对象不同。白盒测试主要针对程序代码逻辑，黑盒测试主要针对程序所展现给用户的功能。



### 4. What is statement testing?

​	Every statement in the component is executed at least once in some test.



​	组件中每条语句在一些测试中被至少执行一次。（语句覆盖）



### 5. What is branch testing?

​	For every decision point in the code, each branch is chosen at least once in some test.



​	对于代码中的每一个决策点，每个分支在一些测试中至少被选择一次。（判定覆盖）

​	

### 6. What is Equivalence partitioning? Give an example to explain.

​	Equivalence partitioning is a black-box technique that divides the input domain of a program into classes of data from which test cases can be derived. For example, If an input condition is Boolean, one valid and one invalid equivalence class are defined.



​	等价划分是一种黑盒技术，它将程序的输入域划分为数据类，从中可以得出测试案例。例如，如果一个输入条件是布尔型，就会定义一个有效的等价类和一个无效的等价类。



### 7. Describe the steps involved in bottom up integration.

​	When this method is used, each component at the lowest level of the system hierarchy is tested individually first. Then, the next components to be tested are those that call the previously tested ones. This approach is followed repeatedly until all components are included in the testing.



​	当使用这种方法时，首先对系统层次结构中最低级别的每个组件进行单独测试。接下来测试那些先前测试调用过的组件。这种方法反复进行直到所有的组件都包括在测试中。



### 8. Describe the steps involved in top down integration.

1. The main control module is used as the test driver, and stubs are substituted for all modules directly subordinate to the main control module.
2. Stubs are replaced either depth first or breadth first.
3. Tests are conducted as each module is integrated.
4. On completion of each set of tests, another stub is replaced with the real module.
5. Regression testing may be conducted to ensure that new errors have not been introduced.



1. 主控制模块被用作测试驱动，存根被替换为所有直接从属于主控制模块的模块。
2. 存根先被替换为深度或广度。
3. 在每个模块被整合时进行测试。
4. 在每一组测试完成后，用真正的模块替换另一个存根。
5. 可以进行回归测试以保证没有引入新的错误。



### 9. What are the differences between the three integration testing strategies?

|                                      | Bottom-up | Top-down | Big-bang | Sandwich |
| :----------------------------------: | :-------: | :------: | :------: | :------: |
|             Integration              |   Early   |  Early   |   Late   |  Early   |
|    Time to basic working program     |   Late    |  Early   |   Late   |  Early   |
|       Component drivers needed       |    Yes    |    No    |   Yes    |   Yes    |
|             Stubs needed             |    No     |   Yes    |   Yes    |   Yes    |
|    Work parallelism at beginning     |  Medium   |   Low    |   High   |  Medium  |
|   Ability to test particular paths   |   Easy    |   Hard   |   Easy   |  Medium  |
| Ability to plan and control sequence |   Easy    |   Hard   |   Easy   |   Hard   |



|                        | 自底向上集成 | 自顶向下集成 | 大爆炸集成 | 三明治集成 |
| :--------------------: | :----------: | :----------: | :--------: | :--------: |
|          集成          |      早      |      早      |     晚     |     早     |
| 产生基本工作程序的时间 |      晚      |      早      |     晚     |     早     |
|    是否需要组件驱动    |      是      |      否      |     是     |     是     |
|    是否需要存根程序    |      否      |      是      |     是     |     是     |
|     启动时的并行性     |     中等     |      低      |     高     |    中等    |
|   测试特殊路径的能力   |     容易     |      难      |    容易    |    中等    |
|  计划和控制顺序的能力  |     容易     |      难      |    容易    |     难     |



### 10. Figure 8.22 illustrates the component hierarchy in a software system. Describe the sequence of tests for integrating the components using a bottom-up approach, a top-down approach, a big-bang approach.

- Figure 8.22:

  ![8.22](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/8.22.png)

- bottom-up approach:

  ![bottom-up](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/bottom-up%20approach.png)

- top-down approach:

  ![top-down](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/top-down%20approach.png)

- big-bang approach:

  ![big-bang](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/big-bang%20approach.png)



### 10. A program is seeded with 25 faults. During testing, 18 faults are detected, 13 of which are seeded faults and 5 of which are indigenous faults. What is the estimate of the number of indigenous faults remaining undetected in the program?

$$
\frac{发现的种子错误s}{总共的种子错误S}=\frac{发现的非种子错误n}{总共的非种子错误N}
$$

$$
N=\frac{Sn}{s}=\frac{25\times5}{13}\approx10,10-5=5
$$



### 11. The following is the pseudo code for the module F1. Please draw its program flowchart.

- Procedure F1 (A:Real; B:Real; Var X: Real)
  Begin
  	If (A>1 AND B==0)
  		Then X:=X/A;
  	If (A==2 Or X>1)
  		Then X:=X+1;
  End
  
- ![flowchart](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/flowchart.png)



### 12. For the module F1 in 11, Can the test case{ A=2, B=0, X=4} achieve statement coverage?Branch Coverage?

- 满足语句覆盖，因为每一个框框都执行了。
- 不满足判定覆盖，因为不是每一个if的真假都进行了测试。



### 13. For the module F1 in 11, Can the test case { A=3, B =0, X=3} and { A=2, B =1, X=1} achieve Branch Coverage? Condition coverage?

- 满足判定覆盖，因为每个if的真假都进行了测试。
- 不满足条件覆盖，因为A<=1,A==1没有进行测试。





