# Company (manager)

## Summery
This project is a company manager tool that allows the manager to manage the employees in the company. The manager can assign shifts, change roles, approve shift swapping, and remove shifts. The manager can also display the information of individual employees. The manager has a unique login to the system that enables them to make changes to the employees in the company. 

### Glosery
---
#### Manager: 
The company leader- a person responsible for monitoring and manage the work for the company this includes changing of shifts and managing the team

#### Employee:
A group of people that is given work by their manager in the company and is separated in different teams


#### Display:
A visual representation of a given subject this could include a visual representation of the employees in the company

#### Unique login:
Is an account with extra privileges, that has access to sensitive information and has the options to edit and change different things in the company. This could include things like the roles of the employees, managing shifts etc.

#### On Demand:
To be able to complete an assignment as soon as it is required/needed.

___

#### User Story 1:
#####  Special login
Description:
As a Manager I want to be able to log in on a unique user that enables me to make changes for the employees, so that it is possible to manage assignments, roles, etc. ensuring the company can continue to run seamlessly.

#### User Story 2:
##### Managing the Employee roles
Description:
As Manager I want to be able to change the individual employees roles however not other managers, so that the team’s structure and responsibilities can be adjusted to optimize project needs and performance.

#### User Story 3:
##### Display
Description:
As Manager I want to visualize the information of individual employees and their times, so that it is possible to easily understand and keep track of said information.

#### User Story 4:
#####  Approval of shift swapping
Description:
As a manager I want to be able to approve the shift swapping between two employees, so that employees can swap shifts easily without disrupting the workflow

#### User Story 5:
##### Assignment of shifts
Description:
As a Manager, I want to be able to assign shifts to employees individually, so that it is possible to assign shifts to employees when needed.

#### User Story 6:
##### Changing shift times
Description:
As a Manager, I want to be able to change employees’ shifts, so that it is possible to change shifts when needed.

#### User Story 7:
##### Removal of shifts
Description:
As a Manager:
I want to be able to remove shifts from employees, so that it is possible to remove shifts when needed.

___

#### Accept criteria: User story 1: 
##### Scenario: Unique login
Given: The manager navigates to the login page. 
When: The manager wants to login.
Then: The manager logs in with a manager account that has more rights.


#### Accept criteria: User story 2: 
##### Scenario: Managing the Employee roles
Given: The manager navigates to the function “Managing the Employee roles”.
When: The manager wants to change the role of the not-manager-employees. 
Then: The manager has the option to choose a not-manager-employee and change their role. 
When: Once the changes are made.
Then: The system should save the changes.

#### Accept criteria: User story 3: 
##### Scenario: Displaying information
Given: The manager access the system to find an employee 
When: The manager navigates to the specific employees profile
Then:  The manager gets access to the employees information


#### Accept criteria: User story 4:
##### Scenario: Approval of shift swapping
Given: The manager access the system
When: The manager has access to various functions such as “Managing the employee roles, Changing shift times, Plan of work hours” and similar features. 
Then: The manager navigates to the "Managing employee roles" section and has the authority to change the roles of non-manager employees. If there are no non-manager employees, a message should be displayed informing about this.
When: The manager navigates to the general overview and is able to view all the different employees in the company.
Given: Two employees wish to swap shifts.
Then: Managers should be able to facilitate the shift swap between the two employees.


#### Accept criteria: User story 5: 
##### Scenario: Assignments of shifts
Given: The manager access the login page to login to a unique user.
When: The manager logs into their unique login They acces a interface (display page) with employees.
Then:  the manager should be able to assign shifts to the employees.




#### Accept criteria: User story 6: 
##### Scenario: Changing of shift times
Given: The manager access the system to change this shift of an employee.
When: The manager navigates to the change-shift page.
Then: The manager can change this shift of a specific user by using the given UI. 


#### Accept criteria: User story 7: 
##### Scenario: Removal of shifts
Given: The manager has logged into their unique login. 
When: The manager has the employees shift display.
Then: The manager can remove individual shifts from the individual employees or multiple shifts from each employee.