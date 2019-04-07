# Introduction
## 1.1 Purpose
The purpose of this document is to present a detailed description of an elementary school management system. Within the description, there will be an explanation of the features and constraints under which the system will operate. This document is intended for both users and stakeholders as a guide for system’s functions.

## 1.2 Scope
This software system is an elementary school management system. The system is design to ease the processes of register and unregister of employees and students as well as the modification of the registers of both. In an specific manner, the system design will allow the secretaries to register, unregister and modify students and employees information. The system will also allow the members of the finance department to make consults, this consults are required in order to calculate employees salaries manually. The school’s principal will also be able to make consults in order to help him in terms of organization and planning.

## 1.3 Definitions, acronyms, and abbreviations
| Term          | Definition           
| ------------- |:-------------:
| Stakeholder                |  Any person with an interest in the project.
| Secretary                 | Person who registers, unregisters and modifies the employees and students information.      
| Finane department members | People who manage the school’s money.
| Principal                 | Person who has executive authority in the school.
| CRUD                      | In computer programming, create, read, update, and delete are the four basic functions of persistent storage.
| Software System           | System software is a type of computer program that is designed to run a computer’s hardware and application programs.


## 1.4 References
https://www.thefreedictionary.com/school+principal
http://www.businessdictionary.com/definition/finance-department.html
https://whatis.techtarget.com/definition/system-software
https://en.wikipedia.org/wiki/Create,_read,_update_and_delete

## 1.5 Overview
This document contains the difficulties that the elementary school is going through because of the lack of a computer system that can help them have control over the register of employees and students that are part of the institution. It also displays the needs and wants of the stakeholders that were identified during the specification process.

As for the next chapter, it contains a general view of the functionality of the product. It describes the requirements in a high-level way and it establishes a connection for the technical requirements specification in the next chapter.
The third chapter is written for stakeholders with more technical acknowledgement because it describes the functionality of the product in technical terms.


# Overall Description
## 2.1 Product perspective
This school management system is aimed toward an elementary school who has an small amount of students and employees, but needs assistance of a software system to manage the students and employees information in order to ease the processes of information handling. Management systems should be user-friendly, easy to learn and use, and it also should be trustworthy. 

This management system is intended to be an standalone application and should not depend on the availability of other software.

### 2.1.1 System Enviroment
![image]()

The School Management System has three active actors and one cooperating 
system. The system is accessed through an executable that will lead the actors to the system’s features. 


## 2.2 Product functions
This section outlines the use cases for each of the active actors of the system. The secretary is the main actor in the system and all of its use cases are done separately, finance department member and the school’s principal have only one use case apiece.

Use case: Register Student 
	Diagram: 
	

Brief Description: 
The secretary accesses the system, then goes to the register student section and fills 	the fields with the student’s information.

Initial Step-By-Step Description
* Before this case use can be initiated, the secretary has already accessed the students register section.
* The secretary fills the fields with the student’s information.
* The secretary clicks the “Register new student” button to save the typed information.
* The system will save the register in an external text file.

Use case: Unregister Student
Diagram: 
	
Brief Description: 
The secretary accesses the system, then goes to the unregister student section and selects the student to me remove from the system.
	
Initial Step-By-Step Description
Before this case use can be initiated, the secretary has already accessed the students unregister section.
* The secretary selects from the list the student whose information is going to be removed from the system. 
* The secretary clicks the “Remove student” button to remove the student from the system.
* The system will erase the register from the external text file.

Use case: Modify student’s information
Diagram: 
	
Brief Description: 
The secretary accesses the system, then goes to the modify student section and selects the student whose information has to be changed and changes the information.
Initial Step-By-Step Description
Before this case use can be initiated, the secretary has already accessed the students modification section.

* The secretary selects from the list the student whose information is going to modified. 
* The secretary fills the fields that need to be modified with the new information.
* The secretary clicks the “Save Changes” button to save changes.
* The information will update from the external file.

Use case: Register Employee
Diagram: 
	
Brief Description: 
The secretary accesses the system, then goes to the register employee section and fills the fields with the employee’s information.
Initial Step-By-Step Description
Before this case use can be initiated, the secretary has already accessed the employees register section.

* The secretary fills the fields with the employee’s information.
* The secretary clicks the “Register new employee” button to save the typed information.
* The system will save the register in an external text file.







## 2.3 User characteristics
+ This subsection of the SRS should describe those general characteristics of the intender users of the product including educational level, experience, and technical expertise.

## 2.4 Constraints
+ This subsection of the SRS should provide a general description of any other items that will limit the developer's options
## 2.5 Assumptions and dependencies
This subsection of the SRS should list each of the factor that affect the requirements stated in the SRS.

# Specific Requirements
+ This section of the SRS should contain all of the software requirements to a leve of detail sufficient to enable desginers to design a system to satisfy those requirements, and testers
  to test that the system satisfies those requirements.

# Appendixes

# Index
