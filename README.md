# CSP Timetable Scheduling

## About the Project

This project is a simple implementation of a **Constraint Satisfaction Problem (CSP)** using Python.

The program creates a timetable for different subjects by assigning available time slots while following given constraints.

## CSP Structure

* **Variables:** Subjects
* **Domains:** Available time slots
* **Constraints:** Subjects that cannot have the same time slot
* **Search:** Backtracking

## Subjects

* Maths
* Python
* DBMS
* AI

## Time Slots

* 9:00 AM
* 11:00 AM
* 2:00 PM

## Constraints

* Maths and Python cannot be scheduled at the same time.
* DBMS and AI cannot be scheduled at the same time.
* Each subject must have exactly one time slot.

## Algorithm Used

**Backtracking Search**

The program tries different time slots for each subject. If a constraint is violated, it goes back and tries another slot.

## Technologies Used

* Python

## Sample Output

```text
FINAL TIMETABLE
----------------
Maths -> 9:00 AM
Python -> 11:00 AM
DBMS -> 9:00 AM
AI -> 11:00 AM
```

## Conclusion

This project shows how CSP and backtracking can be used to solve a simple timetable scheduling problem.
