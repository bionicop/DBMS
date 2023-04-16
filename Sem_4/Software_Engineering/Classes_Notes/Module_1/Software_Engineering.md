---
creation date: 2023-01-19 23:13
modification date: Thursday 19th January 2023
aliases: [Fundamentals of Computer Algorithms]
tags: 
- Fundamentals of Computer Algorithms
---
#publish
<< [[Sem_4/Software_Engineering/Classes_Notes/Module_1/m1_syllabus|Syllabus Module 1]] | [[2022-12-05_Software_Engineering|Software Engineering]] >>

# ❗❓ Info
Course Name: Software Engineering
Course Code: CA255
Date: Thursday 19th January 2023
Professor/Speaker: *self ig..*
Tags: #Software_Engineering

---
# 📑 Software Engineering

## 📃 Summary of Notes
- [Introduction](#introduction)
	- [What is software engineering?](#What%20is%20Software%20Engineering?>)
- [is Software Engineering Art or Science?](<#is Software Engineering Art or Science?>)
- [Program vs Products](<#Program vs Product>)
	- [abc](#abc)

---
# **Introduction**

## **What is Software Engineering?**
- Software is *more than just a program code*.
- On the other hand Engineering is all about *developing products, using well-defined, scientific principles and methods*.
- Thus, It's a *systematic collection* of good program development **practices and techniques**. (An *engineering approach* to *develop a software*.)
- From above points of view we can define Soft Eng as:
	- Soft Eng discusses *systematic & cost-effective* techniques for Software Development.

# *is* **Software Engineering Art or Science?**
- Many people think writing good quality code is an Art. So let's discuss about this:
	- In other engineering branches It is based on science there are *specific rules & names for the components, techniques* & working principles related to it & before they are *standardized the experience is marked as* their **Thumb Rule** and on the basis of it, *the rules are standardized by various organizations*.
	- Likewise in Soft Eng there is *heavy use of knowledge* which comes from **experience of practitioners**, & *well organizations or resarcher's made systmeatically organzied* the experience in ***thoeritical form***.
	- Thus, like any other Engineering Disciplines, *Soft Eng is a "Science" that is **transformed from "Art"***.

---
# **Program** *vs* **Product**
|                                                 **Program**                                                 	|                                                               **Product**                                                               	|
|:-----------------------------------------------------------------------------------------------------------:	|:---------------------------------------------------------------------------------------------------------------------------------------:	|
| Program contains a _set of instructions_ ==designed to complete a specific task==.                          	| Product is the _final manufacture and production of the project_.                                                                       	|
| It is a _passive entity as it resides in the secondary memory_.                                             	| It is an _active entity_ as it is made again and again for the _purpose of distribution to users_.                                      	|
| It exists at a single place and continues to exist until it is deleted.                                     	| A product can _exist for a long period of time as long as it is tested for better **performance and durability**_.                      	|
| It can be made in relatively **shorter** period of _time_.                                                  	| It needs a **lot of time** to be made. There are several stages (_design, coding, testing, maintenance_ etc.) to form a product.        	|
| It is handled by the **Program Managers**.                                                                  	| It is handled by **Product Managers**.                                                                                                  	|
| _Resource requirement isn't necessary_, it only requires **memory space** for ==storing the instructions==. 	| It needs human, technology and time resources to be functional.                                                                         	|
| The _main focus_ of the program is whether it is giving a **specific desired output or not**.               	| The main focus of a product is its _capability to solve the **problem** that it was made for_.                                          	|
| There are _no concrete guidelines_ in writing a program.                                                    	| In case of product, the firm **guidelines are followed**.                                                                               	|
| It _may or may not focus on efficiency and cost_.                                                           	| It needs to _worry about the **cost and efficiency**_ as it would ==affect the profitability of the enterprise launching the product==. 	|

---
# **Emergence of *Software Engineering***
- Early Computer Progrmaming:
	- In the 1950s, computers where slow and expensive even with small line of codes it took computers long time to process them. Since, at that time assembly language was used Porgramming was a very tedious task.
- High Level Programming Language:
	- With the introduction of semi-conductors technology, computers became much smaller and faster as well as cost-effective.
	- Also, programming lanugages were upgraded from assembly(low-level) to high-level lanugage. COBOL and FORTRAN came into existence. As a result programming become much more easier, thus increasing productivity.
- Contorl flow Based Design:
	- Since the usage of computers increased rapidly, and program evolved to become more and more complex, the individual style of programming couldn't be used any longer fro managment or programs.
	- To tackle this the *flowchat technique* was devloped, It is a graphical representation of the sequence of operations carried out to solve a problem.
	- Thus the use of decision-making and looping structures formed the basis of "Structured Programming".
	- Structured Programming helped in writing complex programs more easily, and also made the program efficient and understandable.
- Data flow Oriented Deisgn:
	- With the computer technology becoming more and more powerful, significant devlopments to softwares were made like networking and GUI's, thus making software too complex to be dealt with control flow design.
	- Thus Data-flow oriented design was made. Here, the flow of data through functions or process is displayed through Data-Flow Diagram(DFD).
- Object-Oriented Design:
	- This desing technique revolutionised the software development process. It includes devlopment process. It inclides many new, powerful and real-wprld features like  encapsulation, abstraction, inheritance and polymorphism.
	- These features helped tremendously in development of well-designed and high quality software.

# **Software Devlopment Life Cycle Model**
- SDLC Models are used to define the stages included in an information system development project, from feasibility study till the maintainance of the completed application.

## **Classical Waterfall Model**
- It is the basic SDLC Model, It is very simple but idealistic, This model is not in use anymore, but it's knowledge is improtant as all other SDLC Models are based on this model.
- This model divides the SDLC in various phases. One Phase can be started, only after the completion of the previious phase. *This results in sequential flow of devlopment.*

### **Phases of Waterfall Model:**
- #### **Feasibilty Study:**
	- Main goal of this phase to determine whether devloping a software is *techincally and financially stable or not*.
- #### **Requirement Analysis and Specification:**
	- Main goal is to *understand and document the requirments of the user properly*.
	- *It consistes of 2 differnet activites:*
		- ##### **Requirments Gathering/Analysis:**
			- *All requirments* regarding the **software are gathererd and analysed**.
			- Analysis is done _**to remove incompleteness and inconsistencies in requirments**_.
		- ##### **Requirment Specification:**
			- All the *analysed requirments are documented* in **Software Requirments Specification** (*SRS*) documents.
			- It _serves as a contract b/w developers & customers_.
- #### **Design:**
	- Here, the main goal is to *convert SRS into format which can be implemented in programming language*.
- #### **Coding & Unit Testing:**
	- Here, design is *converted into source code*.
	- Unit testing is *aimed to check whether everything is working properly or not*.
- #### **Integration & System Testing:**
	- Differnet *modules when completed* are **integrated and unit tested**. Integration *takes place in a number of steps*, and during each step, *previously planned modules are integrated* and a *resultant system is obtained*, *which is then tested*. And in the end a *full working system is aquired*.
	- ##### Three Types of Testing:
		- ###### **Alpha Testing**
			- Performed by the development team.
		- ###### **Beta Testing**
			- Performed by selected sutomers.
		- ###### **Acceptance Testing**
			- Customers perform this in order to decide whether to accept or reject the software.