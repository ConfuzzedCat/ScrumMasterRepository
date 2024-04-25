# EPIC: Time Registration and payment system

## Summary

This epic covers the development of time registration and payment systems that will allow employees to register their working hours by punching in and out. The system will also enable managers to view and register timestamps for all employees, set hourly wages, and calculate payments based on recorded working hours and hourly wages.

# Glossary

| Term      | Description                                                             |
| --------- | ----------------------------------------------------------------------- |
| Punch-in  | When the employee clicks "start shift" or checks in.                    |
| Punch-out | When the employee clicks "end shift" or checks out.                     |
| Timestamp | A point in time action that the employee makes when checking in and out |
| Shift     | A period of time that the employee is working.                          |
| Manager   | A person responsible for monitoring and manage the work for the company this includes changing of shifts and managing the team   |
| Employee  | A person who can work in different teams and registers timestamps.                       |
| Company admin  | A person who controls the IT department of the company and can assign new managers  |
| Administrator | A person who administrate the entire system and is employeed by GVS |
| Manager dashboard | A visual representation of a given subject this could include a visual representation of the employees in the company |
| Visitor | A person who is able to view the official pages without acces to the services |
| Welcome page | the start page when you acces the site |
| Reviews | Users of the gvs service reviews |
| Company | The company with a cvr number. GVS´ customer |
| Price points | Display the diffrent pricing of the provided services |
| Tutorial | A guide on how to use the features |
| Contact GVS | a how to get into contact with GVS |
| Payroll periode | from which your salery is calculated typicly from the 20 to the 19 of a month | 
| Soft delete | The illusion of erasure of a given subject that can still be recovered but gets deleted after a given time (gdpr) |
___


## 1. As an employee, I want to punch in at the beginning of my shift, so that I can start recording my work hours accurately.

## 2. As an employee, I want to punch out at the end of my shift, so that I can accurately record when I finish working.

## 3. As an employee, I want to be able to view my total working hours for the day, week, payroll periode, etc, so that I can keep track of my work schedule

## 4. As a manager, I want to be able to handle employees' punch-in and punch-out times for administrative purposes.

## 5. As a manager, I want to be able to set an hourly wage for each employee, so that I can calculate payments based on their working hours.

## 6. As a manager, I want the system to calculate payments for employees based on their recorded working hours and hourly wage, so that I can accurately compensate employees for their work.

___

# Company (manager)

## Summery
This project is a company manager tool that allows the manager to manage the employees in the company. The manager can assign shifts, change roles, approve shift swapping, and remove shifts. The manager can also display the information of individual employees. The manager has a unique login to the system that enables them to make changes to the employees in the company. 


#### User Story 1:
##### Managing the Employee roles
Description:
As Manager I want to be able to change the individual employees roles however not other managers, so that the team’s structure and responsibilities can be adjusted to optimize project needs and performance.

#### User Story 2:
##### Manager dashboard
Description:
As Manager I want to visualize the information of individual employees and their punch-in and punch-out, so that it is possible to easily understand and keep track of said information.

#### User Story 3:
#####  Approval of shift swapping
Description:
As a manager I want to be able to approve the shift swapping between two employees, so that employees can swap shifts easily without disrupting the workflow

#### User Story 4:
##### Assignment of shifts
Description:
As a Manager, I want to be able to assign shifts to employees individually, so that it is possible to assign shifts to employees when needed.

#### User Story 5:
##### Changing shift times
Description:
As a Manager, I want to be able to change employees’ shifts, so that it is possible to change shifts when needed.

#### User Story 6:
##### Removal of shifts
Description:
As a Manager I want to be able to remove shifts from employees, so that it is possible to remove shifts when needed.

#### User Story 7:
##### creating a new employee
Description
as a Manager i want to be able to create new employees and assign them roles so they can log in with their account and register their work


# Group R - Class B - Employee

## Short description and summary

Short description of this Epic: **Employee is the customer’s employees.**

## Summary:
This Epic focuses on employees within the customer of GVS. It introduces features such as viewing shift overviews, selling shifts, flagging shifts for attention, trading shifts with colleagues, requesting available shifts, and tracking total hours worked. These functionalities aim to empower employees to efficiently manage their schedules while ensuring coverage and flexibility in shift arrangements.

## User Stories

### [ 1 Overview of shifts ]
As an employee, I need to be able to see an overview of my shifts, so that both I and my manager know every shift is covered.

### [ 2 Selling a shift ]
As an employee, I need to be able to put a shift up for sale (“buy” is the used lingo for this, don’t get confused), so that we, the employees, can handle shift swapping by ourselves, with our manager accepting these changes in the end.

### [ 3 Flag a shift ]
As an employee, I need to be able to flag a shift if I want to swap it or am completely unable to attend, so it can be taken care of in due time.

### [ 4 Trading a shift ]
As an employee, I need to be able to swap shifts with my colleagues, so that we can help each other out and ensure our shift schedule runs smoothly.

### [ 5 Requesting an available shift ]

As an employee, I need to be able to request an available shift, so that I can cover an open shift if needed.



# Visitor behaviour

## Summary:
This epic is concerned with every function that is available to visitors, meaning users who are not already signed up to GVS’s services. 

## User stories: 
#### User story 1
As a visitor I want to be met by a simple and welcoming page that shows the purpose of GVS and provides a possibility to read user reviews, so that I get an initial level of understanding and trust towards GVS and its services. 

#### User story 2
As a visitor I want to be able to create an account for my company, so that I am able to use GVS’s services.

#### User story 3
As a visitor I want to be able to see the pricing of available services, so that I am able to determine if the services fit my budget.

#### User story 4
As a visitor I want to be able to see a tutorial of how the system is used/ an overview of the system's functionality. So that I can get a basic understanding of how to use the product for my company.

#### User story 5
As a visitor I want to be able to contact GVS with questions, queries and feedback, so that my questions, concerns, etc. can be addressed before becoming a member. 

#### User story 6
As a visitor I want to be able to log in as my assigned role so that i am able to access features which correspond to my roles


**User Story 1: Creation**

**As an** administrator:

**I want** to create a new user account in the system

**So that** new users can access the necessary resources.

**User Story 2: soft Deletion of User Accounts upon Termination/Firing**

**As an** administrator:

**I want to** soft delete a user account from the system

**So that** former users no longer have access to the organization's data and resources.

**User Story 3: Editing User and company Information and Passwords**

**As an** administrator:

**I want to** edit user and company information such as name, contact information, and passwords

**So that** user and company data remains accurate and up-to-date.

**User Story 4: Administration of Access to Functions and Data**

**As an** administrator:

**I want to** administer access to various functions and data for users based on their roles and responsibilities

**So that** users only have access to necessary information to perform their job.

**User Story 5: Assignment of Users to Departments or Locations**

**As an** administrator:

**I want to** assign users to specific departments or locations in the organization

**So that** user access is organized and structured according to their work area.

**User Story 6: Temporary Deactivation of User Accounts**

**As an** administrator:

**I want to** temporarily deactivate a user account as needed

**So that** only active and authorized users have access to the system.
