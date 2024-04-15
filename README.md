Oracle Database Management Task
Overview

This task involves managing an Oracle database for an organization, including creating users, tables, transactions, sessions, and functions.
Task Details
a) User and Role Creation

    Create a Manager User with privileges to create users.
    Grant the Manager User a role with privileges to create two additional users.
    Let User 1 create the Employee and Department tables.
    Let User 2 insert 5 rows of employees into the Employees table.

b) Blocker-Waiting Situation

    Demonstrate a blocker-waiting situation between User 1 and User 2.
    Implement a transaction in User 1 that raises the salary rate by 10% for employees in department 1.

c) Session Identification

    Identify the sessions involved in the blocker-waiting situation using SID and serial# for both blocker and waiting sessions.

d) Deadlock Scenario

    Demonstrate a deadlock scenario and display the expected result.

e) Functions

    Create a function that calculates the average salary for any department.
    Create a function that calculates the total salary in a department.
    Create a function that calculates the maximum salary in a department.
