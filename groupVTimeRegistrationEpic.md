# EPIC: Time Registration and payment system

# Glossary

| Term      | Description                                                             |
| --------- | ----------------------------------------------------------------------- |
| Punch-in  | When the employee clicks "start shift" or checks in.                    |
| Punch-out | When the employee clicks "end shift" or checks out.                     |
| Timestamp | A point in time action that the employee makes when checking in and out |
| Shift     | A period of time that the employee is working.                          |
| Manager   | A person with administrative rights to view and register timestamps.    |
| Employee  | A person who is working and registers timestamps.                       |

## 1. As an employee, I want to punch in at the beginning of my shift, so that I can start recording my work hours accurately.

### Acceptance:

- given the employee has a shift, when the employee punches in, then we register the current timestamp
- given an employee tries to punch in and hasn't ended their previous shift, we dispay an error message

## 2. As an employee, I want to punch out at the end of my shift, so that I can accurately record when I finish working.

### Acceptance:

- Given the employee has forgot to punch in, when the employee tries to punch out, then the punch out isn't registered and a error message is shown
- Given the employee punches out, when the shift is done, then they recieve a timestamp corresponding to the amount of hours and minuttes worked for that timeframe

## 3. As an employee, I want to be able to view my total working hours for the day, week, etc, so that I can keep track of my work schedule and earnings.

### Acceptance:

- I can see an overview of my working hours for different time periods based on punch-in and punch-out timestamps.
- I should be able to see what I have earned based on my hourly wage and working hours.
- I should be able to see which hours have been paid and which are still pending.

## 4. As a manager, I want to be able to handle employees' punch-in and punch-out times for administrative purposes.

### Acceptance:

- I can interact with individual timestamps for each employee for administrative crud tasks.
- Only a manager or above should be able to view and register timestamps for all employees.
- Given the manager has enlisted employees, when they want to verify timestamps for an individual employee, then they have rights to view and register timestamps for all their employees

## 5. As a manager, I want to have an overview of all employees' punch-in and punch-out times, so that I can monitor working hours and ensure compliance.

### Acceptance:

- Given timestamps for all employees are recorded, Then I should be able to extract a list of employees and their timestamps for control of working hours and fraud prevention.

## 6. As a manager, I want to be able to set an hourly wage for each employee, so that I can calculate payments based on their working hours.

### Acceptance:

- Only a manager or above should be able to set the hourly wage for an employee.

## 7. As a manager, I want the system to calculate payments for employees based on their recorded working hours and set hourly wage, so that I can accurately compensate employees for their work.

### Acceptance:

- Given the system has recorded working hours and set hourly wages for employees, when I request payment calculation for a specific time period, then the system accurately calculates payments for each employee based on their recorded working hours and hourly wage.
- The calculated payments should be displayed clearly, showing the total amount owed to each employee for the specified time period.
- The system should provide the ability to generate payment reports for individual employees as well as for all employees collectively.
- Only managers or above should have access to initiate payment calculations and view payment reports.
