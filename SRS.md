### UNIVERSIDAD AUTÓNOMA DE CIUDAD JUÁREZ

### DIVISIÓN MULTIDISCIPLINARIA EN CIUDAD UNIVERSITARIA

### DEPARTAMENTO DE INGENIERÍA ELÉCTRICA Y COMPUTACIÓN


![](http://www.uacj.mx/comunicacion/PublishingImages/Escudo%20UACJ%202015/Escudo%20uacj%202015-color-sin%20fondo.png)

### School Management System SRS

#### EDGAR OMAR REYES OLIVAS
#### 169818

#### Cd.Juárez, Chih., México
#### May 16, 2019






# 1. Introduction
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


# 2. Overall Description
## 2.1 Product perspective
This school management system is aimed toward an elementary school who has an small amount of students and employees, but needs assistance of a software system to manage the students and employees information in order to ease the processes of information handling. Management systems should be user-friendly, easy to learn and use, and it also should be trustworthy. 

This management system is intended to be an standalone application and should not depend on the availability of other software.

### 2.1.1 System Enviroment
![systemenviroment](https://github.com/RequirementEngineering/ch-re-al169818EdgarReyes/blob/master/artifacts/Use%20Cases/System%20Enviroment.png?raw=true)

The School Management System has three active actors and one cooperating 
system. The system is accessed through an executable that will lead the actors to the system’s features. 


## 2.2 Product functions
This section outlines the use cases for each of the active actors of the system. The secretary is the main actor in the system and all of its use cases are done separately, finance department member and the school’s principal have only one use case apiece.

### 2.2.1 Secretary Use Cases

Use case: Register Student 
Diagram: 

![uc1](https://github.com/RequirementEngineering/ch-re-al169818EdgarReyes/blob/master/artifacts/Use%20Cases/UC1.png?raw=true)
	

Brief Description: 
The secretary accesses the system, then goes to the register student section and fills 	the fields with the student’s information.

Initial Step-By-Step Description
* Before this case use can be initiated, the secretary has already accessed the students register section.
* The secretary fills the fields with the student’s information.
* The secretary clicks the “Register new student” button to save the typed information.
* The system will save the register in an external text file.

Use case: Unregister Student
Diagram: 

![uc2](https://github.com/RequirementEngineering/ch-re-al169818EdgarReyes/blob/master/artifacts/Use%20Cases/UC2.png?raw=true)
	
Brief Description: 
The secretary accesses the system, then goes to the unregister student section and selects the student to me remove from the system.
	
Initial Step-By-Step Description
Before this case use can be initiated, the secretary has already accessed the students unregister section.
* The secretary selects from the list the student whose information is going to be removed from the system. 
* The secretary clicks the “Remove student” button to remove the student from the system.
* The system will erase the register from the external text file.

Use case: Modify student’s information
Diagram: 

![uc3](https://github.com/RequirementEngineering/ch-re-al169818EdgarReyes/blob/master/artifacts/Use%20Cases/UC3.png?raw=true)

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

![uc4](https://github.com/RequirementEngineering/ch-re-al169818EdgarReyes/blob/master/artifacts/Use%20Cases/UC4.png?raw=true)

Brief Description: 
The secretary accesses the system, then goes to the register employee section and fills the fields with the employee’s information.
Initial Step-By-Step Description
Before this case use can be initiated, the secretary has already accessed the employees register section.

* The secretary fills the fields with the employee’s information.
* The secretary clicks the “Register new employee” button to save the typed information.
* The system will save the register in an external text file.


Use case: Unregister Employee
Diagram: 
![unr](https://github.com/RequirementEngineering/ch-re-al169818EdgarReyes/blob/master/artifacts/Use%20Cases/UC5.png?raw=true)

Brief Description: 
The secretary accesses the system, then goes to the unregister employee section and selects the employee to be removed from the system.

Initial Step-By-Step Description
Before this case use can be initiated, the secretary has already accessed the employees unregister section.

* The secretary selects from the list the employee whose information is going to be removed from the system. 
* The secretary clicks the “Remove Employee” button to remove the employee from the system.
* The system will erase the register from the external text file.

Use case: Modify employee’s information
Diagram: 

![uc5](https://github.com/RequirementEngineering/ch-re-al169818EdgarReyes/blob/master/artifacts/Use%20Cases/UC6.png?raw=true)
	
Brief Description: 
The secretary accesses the system, then goes to the modify employee section and selects the employee whose information has to be changed and changes the information.
Initial Step-By-Step Description
Before this case use can be initiated, the secretary has already accessed the employees modification section.

* The secretary selects from the list the employee whose information is going to modified. 
* The secretary fills the fields that need to be modified with the new information.
* The secretary clicks the “Save Changes” button to save changes.
* The information will update from the external file.

Use case: Consult Students Information
Diagram: 

![uc6](https://github.com/RequirementEngineering/ch-re-al169818EdgarReyes/blob/master/artifacts/Use%20Cases/UC7.png?raw=true)

Brief Description: 
	The secretary accesses the system, then goes to the registered students section and search in the list for the student whose information needs to be consulted
	Initial Step-By-Step Description
	Before this case use can be initiated, the secretary has already accessed the registered students section.

The secretary selects from the list the student whose information needs to be consulted. 


Use case: Consult Employees Information
Diagram: 

![cei](https://github.com/RequirementEngineering/ch-re-al169818EdgarReyes/blob/master/artifacts/Use%20Cases/UC9.png?raw=true)

Brief Description: 
The secretary accesses the system, then goes to the registered employees section and search in the list for the employee whose information needs to be consulted

Initial Step-By-Step Description
Before this case use can be initiated, the secretary has already accessed the registered employee section.

* The secretary selects from the list the student whose information needs to be consulted. 

### 2.2.1 Finance Department Members Use Cases
Use case: Consult Students Information
Diagram: 

![](https://github.com/RequirementEngineering/ch-re-al169818EdgarReyes/blob/master/artifacts/Use%20Cases/UC8.png?raw=true)

Brief Description: 
A member of the finance department accesses the system, then goes to the registered students section and search in the list for the student whose information needs to be consulted

Initial Step-By-Step Description
Before this case use can be initiated, the member of the finance department has already accessed the registered students section.

* A member of the finance department selects from the list the student whose information needs to be consulted. 

Use case: Consult Employees Information
Diagram: 

![](https://github.com/RequirementEngineering/ch-re-al169818EdgarReyes/blob/master/artifacts/Use%20Cases/UC8.png?raw=true)

Brief Description: 
A member of the finance department accesses the system, then goes to the registered employees section and search in the list for the employee whose information needs to be consulted

Initial Step-By-Step Description
Before this case use can be initiated, the member of the finance department has already accessed the registered employee section.

* A member of the finance department selects from the list the student whose information needs to be consulted. 

### 2.2.1 School's Principal Use Cases
Use case: Consult Students Information
Diagram: 

![](https://github.com/RequirementEngineering/ch-re-al169818EdgarReyes/blob/master/artifacts/Use%20Cases/UC11.png?raw=true)

Brief Description: 
The school’s principal accesses the system, then goes to the registered students section and search in the list for the student whose information needs to be consulted

Initial Step-By-Step Description
Before this case use can be initiated, the school’s principal has already accessed the registered students section.

* The school’s principal selects from the list the student whose information needs to be consulted. 

Use case: Consult Employees Information
Diagram: 

![](https://github.com/RequirementEngineering/ch-re-al169818EdgarReyes/blob/master/artifacts/Use%20Cases/UC12.png?raw=true)

Brief Description: 
The school’s principal accesses the system, then goes to the registered employees section and search in the list for the employee whose information needs to be consulted

Initial Step-By-Step Description
Before this case use can be initiated, the member of the school’s principal has already accessed the registered employee section.

* The school’s principal selects from the list the student whose information needs to be consulted. 

## 2.3 User characteristics
| User       	| Characteristics         
| ------------- |:-------------:
| Secretary     | The secretary is the person or people who will be using all the features of the system, this includes register, unregisters and changes to the information of both employees and students. The secretary is expected to have basic notions in the interaction  with computer applications.
| Finance Department Members      | The member of the finance department will be using the system only to generate consults in order to help them with salary estimates. This people are expected to have basic notions in the interaction  with computer applications.    
| Principal | The school’s principal will be using the system only to generate consults to help him with the organization and planning of the school. The principal is expected to have basic notions in the interaction  with computer applications.     


## 2.4 Constraints
This School Management System is a single-user software.

## 2.5 Assumptions and dependencies
It is assumed that the computer in which this software is running has Windows 10 as the operative system. 


# 3. Specific Requirements
## 3.1 Functional Requirements

Description of functional requirements by giving various use cases.

#### Use Case 1: Student Registration
##### Primary Actor: Secretary
##### Precondition: The secretary is already in the student register section.
##### Main Scenario: 

1. Secretary fills every empty field of the registration form with the student’s information.
2. After filling the fields, the secretary clicks on the button “Register New Student” to make a new register of the new student.
3. The register is done and the system saves it on an external text file that has all the student’s registers.

#### Use Case 2: Student Unregistration
##### Pr# imary Actor: Secretary
##### Preondition: The secretary is already in the student unregister section.
##### Main Scenario: 

1. From a list that is shown the secretary needs to search for the student who is going to be removed from the system.
2. Once that the student has been found the secretary selects it.
3. After selecting the student from the list the secretary clicks the “Remove Student” button to remove the student’s register from the system.
4. The register is erased from the external text file.

#### Use Case 3: Student’s Information Modification
##### Primary Actor: Secretary
##### Precondition: The secretary is already in the student modification section.
##### Main Scenario: 

1. From a list that is shown the secretary needs to search for the student whose information has to modified.
2. Once that the student has been found the secretary selects it.
3. After selecting the student from the list the secretary clicks the “Modify Student” button to go to a new Panel that is going to contain all the student information fields.
4. Once in this new Panel, the secretary must overwrite the necessary fields.
5. After modifying the information the secretary clicks the “Save Changes” button to save changes.
6. Information will be updated from the external text file.

#### Use Case 4: Student’s Information Consult
##### Primary Actor: Secretary
##### Precondition: The secretary is already in the registered students section.
##### Main Scenario: 

1. From a list that is shown the secretary needs to search for the student whose information wants to be consulted.
2. Once found the information will be shown in a new Panel where the user can’t edit the information.

#### Use Case 5: Employee Registration
##### Primary Actor: Secretary
##### Precondition: The secretary is already in the employee register section.
##### Main Scenario: 

1. Secretary fills every empty field of the registration form with the employee information.
2. After filling the fields, the secretary clicks on the button “Register New Employee” to make a new register of the new employee.
3. The register is done and the system saves it on an external text file that has all the employee’s registers.

#### Use Case 6: Employee Unregistration
##### Primary Actor: Secretary
##### Precondition: The secretary is already in the employee unregister section.
##### Main Scenario: 

1. From a list that is shown the secretary needs to search for the employee who is going to be removed from the system.
2. Once that the employee has been found the secretary selects it.
3. After selecting the employee from the list the secretary clicks the “Remove Employee” button to remove the employee’s register from the system.
4. The register is erased from the external text file.

#### Use Case 7: Employee’s Information Modification
##### Primary Actor: Secretary
##### Precondition: The secretary is already in the employee modification section.
##### Main Scenario: 

1. From a list that is shown the secretary needs to search for the employee whose information has to modified.
2. Once that the employee has been found the secretary selects it.
3. After selecting the employee from the list the secretary clicks the “Modify Employeet” button to go to a new Panel that is going to contain all the employee information fields.
4. Once in this new Panel, the secretary must overwrite the necessary fields.
5. After modifying the information the secretary clicks the “Save Changes” button to save changes.
6. Information will be updated from the external text file.

#### Use Case 8: Employee’s Information Consult
##### Primary Actor: Secretary
##### Precondition: The secretary is already in the registered employees section.
##### Main Scenario: 

1. From a list that is shown the secretary needs to search for the employees whose information wants to be consulted.
2. Once found the information will be shown in a new Panel where the user can’t edit the information.

#### Use Case 9: Student’s Information Consult
##### Primary Actor: School’s Principal and Members of the Finance Department
##### Precondition: The user is already in the registered students section.
##### Main Scenario: 

1. From a list that is shown the user needs to search for the student whose information wants to be consulted.
2. Once found the information will be shown in a new Panel where the user can’t edit the information.

#### Use Case 10: Employee’s Information Consult
##### Primary Actor: School’s Principal and Members of the Finance Department
##### Precondition: The user is already in the registered employees section.
##### Main Scenario: 

1. From a list that is shown the user needs to search for the employees whose information wants to be consulted.
2. Once found the information will be shown in a new Panel where the user can’t edit the information.

# 4. Processes

## 4.1 Student Enrollment

This process is divided in two types of enrollments, the first one is for the new students and the second one is for students who are already in the school and that are going to enroll into a new scholar year.

The process of the students who are already in the school is the following.

The student has to generate a voucher and there are two ways of doing this. The first one is through the school's website and the second
one is going to the school and ask for the voucher in the scholar services department. Using either way, the student will get a voucher
and a copy of the original voucher.

After having generated the vouchers the student has to pay the enrollment fee that is specified in the voucher. To do this the student has to go to the bank which the school has an agreement with. In the bank the student has to go to the paying booth and deliver both vouchers along with the enrollment fee. After the bank employee validates the payment a stamped voucher is delivered to the student.

The next step is to deliver de voucher's copy in the school, more specifically, in the human resources department where an employee will receive the copy and register the student's information in the system.

![](https://github.com/RequirementEngineering/ch-re-al169818EdgarReyes/blob/master/artifacts/bpm%20diagrams/bp1.png?raw=true)

![](https://github.com/RequirementEngineering/ch-re-al169818EdgarReyes/blob/master/artifacts/bpm%20diagrams/bp2.png?raw=true)

![](https://github.com/RequirementEngineering/ch-re-al169818EdgarReyes/blob/master/artifacts/bpm%20diagrams/bp3.png?raw=true)



















