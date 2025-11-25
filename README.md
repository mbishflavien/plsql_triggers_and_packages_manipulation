# PL/SQL Triggers and Packages Manipulation
## Group members:
### 1. MBISHIBISHI Flavien 27857
### 2. Uwamwezi Denyse  27976
### 
### 


#### 1. What This Repository Contains

##### This repository includes all the PL/SQL work done for practicing and demonstrating triggers, packages, and general database logic in Oracle. It covers system access rules, dynamic SQL, salary calculations, and security context.

### 2. Triggers — System Access Control
What the Trigger Work Was About:
-Users cannot access or modify data on Saturday and Sunday
-Access is only allowed Monday to Friday, from 8:00 AM to 5:00 PM
-Any operation attempted outside allowed hours or days must be blocked
-Every blocked attempt should be logged automatically

#### Objective

To demonstrate how triggers can enforce real-time security rules and handle automatic auditing in the database.

### 3. Packages — Salary and Dynamic SQL Management
What the Package Work Was About

-A function to calculate RSSB tax (5%) and return the net salary
-A procedure using EXECUTE IMMEDIATE to run dynamic SQL (create/update tables, etc.)
-Demonstrations of USER, CURRENT_USER, DEFINER RIGHTS, and INVOKER RIGHTS
-Example calls showing how the function and procedure behave

#### Objective

To show how to build PL/SQL packages, use dynamic SQL properly, and understand Oracle’s security context mechanisms.

#### 4. Repository Structure

Triggers/ — Access control trigger scripts

Packages/ — Package specification and body

Screenshots/ — Execution proofs and logs

README.md — Documentation


#### 5. How to Test the Scripts

-Connect to Oracle SQL Developer or SQL*Plus

-Run required table creation scripts

-Run the package specification

-Run the package body

-Run the trigger scripts

-Test using INSERT / UPDATE / DELETE

-Verify blocked actions and salary outputs


#### 6. Purpose of This Work

This project demonstrates:

-How triggers enforce business and security rules

-How packages organize functions and procedures

-How dynamic SQL works in Oracle

-How security context affects PL/SQL execution
