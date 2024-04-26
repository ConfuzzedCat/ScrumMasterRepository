# Group R - Class B - Employee

## Short description and summary

Short description of this Epic: **Employee is the customer’s employees.**

Summary:
This Epic focuses on employees within the customer of GVS. It introduces features such as viewing shift overviews, selling shifts, flagging shifts for attention, trading shifts with colleagues, requesting available shifts, and tracking total hours worked. These functionalities aim to empower employees to efficiently manage their schedules while ensuring coverage and flexibility in shift arrangements.

[Figma Wireframe](https://www.figma.com/file/HP6q9ZMzGzcP7QbLuuagoz/GVS-Employee-Wireframe?type=design&node-id=0-1&mode=design&t=UBH1B2rOPIuu0Mh0-0)

## Glossary

| Term      | Description                                                             |
| --------- | ----------------------------------------------------------------------- |
| Shift     | A period of time that the employee is working.                          |
| Manager   | A person with administrative rights to view and register shifts.        |
| Employee  | A person who is working and registers shift.                            |

## User Stories

### [ 1 Overview of shifts ]
As an employee, I need to be able to see an overview of my shifts, so that both I and my manager know every shift is covered.

AC:
Given an employee is logged into the system
When they navigate to the shift schedule page
Then they should see both old and current shifts displayed


### [ 2 Selling a shift ]
As an employee, I need to be able to put a shift up for sale (“buy” is the used lingo for this, don’t get confused), so that we, the employees, can handle shift swapping by ourselves, with our manager accepting these changes in the end.

AC:
Given an employee is logged into the system
When they navigate to their profile or availability settings
Then they should have the option to toggle their availability for shifts

### [ 3 Flag a shift ]
As an employee, I need to be able to flag a shift if I want to swap it or am completely unable to attend, so it can be taken care of in due time.

AC:
Given a manager is logged into the system
When they create a new shift
Then they should have the option to toggle the shift status as "taken" or "available"

### [ 4 Trading a shift ]
As an employee, I need to be able to swap shifts with my colleagues, so that we can help each other out and ensure our shift schedule runs smoothly.

AC:
Given an employee has requested a shift swap - And the other employee has also requested the same shift
When both employees confirm the swap request
Then the shifts should swap places

### [ 5 Requesting an available shift ]

As an employee, I need to be able to request an available shift, so that I can cover an open shift if needed.

AC:
Given an employee sees an available shift they want
When they select the shift
Then there should be an option to request the shift
