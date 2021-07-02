---
title: Software_Engineering
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

​	Software engineers use their knowledge of computers and computing to help solve problems.Software engineers use techniques, tools, procedures, and paradigms to enhance the quality of their software products. Their aim is to use efficient and productive approaches to generate effective solutions to problems. Instead of investigating hardware design or proving theorems about how algorithms work, a software engineer focuses on the computer as a problem-solving tools.



### 2. What is good software?

​	Good software engineering must always include a strategy for producing quality software. But before we can devise a strategy, we must understand what we mean by quality software.

1. The quality of the product.
2. The quality of the process.
3. Quality in the context of the business environment.



### 3. What are 9 activities in software development?

1. requirements analysis and definition
2. system design
3. program design
4. writing the programs (program implementation)
5. unit testing
6. integration testing
7. system testing
8. system delivery
9. maintenance



### 4. How has software engineering changed?

1. criticality of time-to-market for commercial products
2. shifts in economics of computing: lower HW, higher development/maintenance costs
3. availability of powerful desktop computing
4. extensive local- and wide-area networking
5. availability and adoption of OO technology
6. graphical user interfaces
7. unpredictability of waterfall model of development



### 5. What is the Wasserman's discipline of software engineering?

1. abstraction
2. analysis and design methods and notations
3. user interface prototyping
4. software architecture
5. software process
6. reuse
7. measurement
8. tools and integrated environments



## Chapter 2

### 1. What are the drawbacks of the Waterfall model?

1. The model provides no guidance to managers and developers on how to handle changes to products and activities that are likely to occur during development.
2. It does not treat software as a problem-solving process. It was derived from a manufacturing view of software development. Software is a creation process, not a manufacturing process. Creation usually involves trying a little of this or that, developing and evaluating prototypes, assessing the feasibility or requirements, contrasting several designs, learning from failure, and eventually setting on a satisfactory solution to the problem at hand.
3. The biggest problem with the waterfall model is that it does not reflect the way code is really developed.

### 2. What are the benefits of the Incremental Model and Iterative Model?

1. Training can begin on an early release, even if some functions are missing.
2. Markets can be created early for functionality that has never before been offered.
3. Frequent releases allow developers to fix unanticipated problems globally and quickly, as they are reported from the operational system.
4. The development team can focus on different areas of expertise with different releases.



## Chapter 4

### 1. Describe the process of determining requirements.

1. Elicitation: Collecting the user's requirements.
2. Analysis: Understanding and modeling the desired behavior.
3. Specification: Documenting the behavior of the proposed software system.
4. Validation: Checking that our specification matches the user's requirements.



### 2. It is usually helpful to separate the requirements into three categories. What are these three categories? Explain why it is helpful.

1. Three categories are:
   - Requirements that absolutely must be met.
   - Requirements that are highly desirable but not necessary.
   - Requirements that are possible but could be eliminated.
2. Reasons: The analysis of requirements by category is helpful to all parties in understanding what is really needed. It is also useful when a software development project is constrained by time or resources; if the system as defined will cost too much or take too long to develop, category 3 requirements can be dropped and category 2 requirements can be analyzed for elimination or postponement.



### 3. What is a requirements definition document? What is a requirements specification document?

1. The requirements definition is a complete listing of everything the customer expects the proposed system to do. It represents an understanding between the customer and developer of what the customer needs or wants, and it is usually written jointly by the customer and developer.
2. The requirements specification restates the requirements definition in technical terms appropriate for the development of a system design; it is the technical counterpart to the requirements definition document, and it is written by requirements analysts.



### 4. What is a functional requirement? Give an example to explain.

​	A functional requirement describes an interaction between the system and its environment.( For example, to determine functional requirements, we decide what states are acceptable ones for the system to be in.) Further, functional requirements describe how the system should behave given certain stimuli.



### 5. What is a nonfuctional requirement? Give an example to explain.

​	A nonfuctional requirement, or quality requirement, or constraint, describes a restriction on the system that limits our choices for construction a solution to the problem. (For instance, we may be the system must be developed on an Aardvark computer or that the paychecks must be distributed to the employees no more than four hours after the initial data are read. Similarly, we may be told that queries to the system must be answered within three seconds.) These constraints usually narrow our selection of language, platform, or implementation techniques or tools; however, the selection is made at the design stage, after the requirements have been specified.



### 6. The following is the requirements of a system. Please draw its data flow diagram.

- 某银行计算机储蓄系统的工作过程大致如下：储户填写的存款单或取款单由业务员键入系统,如果是存款则系统记录存款人姓名、住址(或电话号码)、身份证号码、存款类型、存款日期、到期日期、利率及密码等信息，并印出存款单给储户；如果是取款而且存款时留有密码，则系统首先核对储户密码，若密码正确或存款时未留密码，则系统计算利息并印出利息清单给储户。请对以上问题画出分层数据流图。
- ![基本模型](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/Chapter5_first.png)
- ![第一级模型](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/Chapter5_second.png)
- ![第二级模型](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/Chapter5_third.png)



## Chapter 5

### 1. For each type of coupling, give an example of two components coupled in that way.

1. Content coupling: Content coupling might occur when one component modifies an internal data item in another component, or when one component branches into the middle of another component.
2. Common coupling: If data are accessible from a common data store, common coupling occurs.
3. Control coupling: When on component passes parameters to control the activity of another component, we say that there is control coupling between the two.
4. Stamp coupling: When a data structure is used to pass information from one component to another, and the data structure itself is passed, there is stamp coupling between the components.
5. Data coupling: If only data are passed, the components are connected by data coupling.



### 2. For each type of cohesion, write a description of a component exhibiting that kind of cohesion.

1. Coincidental: The worst degree of cohesion, coincidental, is found in a component whose parts are unrelated to one another.
2. Logical cohesion: Logical is the next higher level of cohesion( though still not desirable), where several logically related functions or data elements are placed in the same component.
3. Temporal: Sometimes a component is used to initialize a system or a set of variables. Such a component performs several functions in sequence, but the functions are related only by the timing involved, so its cohesion is temporal.
4. Procedurally cohesive: When functions are grouped together in a component just to ensure this order, the component is procedurally cohesive.
5. Communicationally cohesive: Modules that are designed around data sets in the way that associate certain functions because they operate on the same data set are communicationally cohesive.
6. Sequential cohesion: If the output from one part of a component is input to the next part, the component has sequential cohesion.
7. Functional cohesion: Every processing element is essential to the performance of a single function, and all essential elements are contained in one component.



### 3. 画出下列伪码程序的程序流程图。

- ```
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
  ```

- ![程序流程图](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/Chapter5.png)



## Chapter 6

### 1. What are major characteristics of object orientation?

1. identity
2. abstraction
3. classification
4. encapsulation
5. inheritance
6. polymorphism
7. persistence



### 2. What is the key difference between more traditional procedural development and the OO development?

​	The across-the-process consistency is a key difference between more traditional procedural development and the OO development process. OO is a philosophy of problem and solution representation, not a software life cycle by itself.

​	

### 3. What is a use case?

​	A use case describes particular functionality that a system is supposed to perform or exhibit by modeling the dialog that a user, external system, or other entity will have with the system to be developed.



### 4. Draw a use case diagram for the ATM problem.

![ATM use case](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/ATM_usecase.png)

### 5. Classify each of the following relationships as either an inheritance relationship, an aggregation relationship, or a general association.

1. Person──Student: an inheritance relationship
2. Library──Library patron: an aggregation relationship
3. Car──Driver: a general association



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



### 10. Please draw a class diagram for 9.

![Royal class 1](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/Royal.png)

### 11. Use the noun-in-text-description to identify the classes from the above requirement statement.

- The station manager uses the system to control inventory. The system will warn of low inventory and automatically order new parts and fuel.
- Classes: system, manager, inventory, fuel, parts.



### 12. Please draw a class diagram for 11.

![Royal class 2](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/Royal_second.png)



### 13. Please draw the state diagrams for the fuel and parts classes.

![Royal state diagram](https://oliver-picture.oss-cn-beijing.aliyuncs.com/Software/Royal_state_diagram.png)



## Chapter 8

### 1. What are the main software testing objectives?

1. Testing is the process of executing a program with the intent of finding errors.
2. A good test case is one with a high probability of finding an as-yet undiscovered error.
3. A successful test is one that discovers an as-yet-undiscovered error.




### 2. Explain the following terms: Unit test, integration test, function test, performance test, acceptance test.

1. Unit test: Unit test verifies that the component functions properly with the types of input expected from studying the component's design. Each program component is tested on its own, isolated from the other components in the system.
2. Integration test: Integration testing is the process of verifying that the system components work together as described in the system and program design specifications. It ensures that the interfaces among the components are defined and handled properly.
3. Function test: A function test evaluates the system to determine if the functions described by the requirements specification are actually performed by the integrated system. We test the system to ensure that it has the desired functionality. The result is a functioning system. 
4. Performance test: A performance test compares the system with the remainder of these software and hardware requirements.
5. Acceptance test: An acceptance test makes certain that the system works according to customer expectations. We join the customer to perform an acceptance test, where the system is checked against the customer's requirements description.



### 3. What are the differences between black box and white box testing?

1. Black-box testing: Knowing the specified function a product is to perform, tests  can be conducted that demonstrate each function is fully operational, at the same time searching for errors in each function.
2. White-box testing: Knowing the internal workings of of all independent logic paths. White-box testing is a test case design method that uses the  control structure of the procedural design to derive test cases. 



### 4. What is statement testing?

​	Every statement in the component is executed at least once in some test.



### 5. What is branch testing?

​	For every decision point in the code, each branch is chosen at least once in some test.



### 6. What is Equivalence partitioning? Give an example to explain.

​	Equivalence partitioning is a black-box technique that divides the input domain of a program into classes of data from which test cases can be derived. An ideal test case uncovers a class of errors that might require many arbitrary test cases to be executed before a general error is observed.



### 7. Describe the steps involved in bottom up integration.

​	When this method is used, each component at the lowest level of the system hierarchy is tested individually first. Then, the next components to be tested are those that call the previously tested ones. This approach is followed repeatedly until all components are included in the testing.



### 8. What are the differences between the three integration testing strategies?





















