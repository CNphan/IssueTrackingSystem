# IssueTrackingSystem
An issue tracking system that allows managers to manage the status of a task. 

## **Screen 1: List of Open Defects (Tickets) - Default Screen**
---
* Defect name 
* Summary 
* Assignee 
* Split Screen or Bootstrap Modal on single Defect ( Update Information)
* Create Button: Creates the ticket - Link to Screen 2 

## **Screen 2: Ticket Submission Screen**
---
* Project Name : Drop-down -must exist in DB
* Defect Name : pre-pop (incremental with unique identifier)
* Summary 
* Status : Open (Default), In-Progress, Closed 
* Priority: Drop-down :: Low, Medium, High 
* Assignee: Select from existing 
* Description 

##**Screen 3: Ticket Submission Modal**
---
* Defect Name 
* Summary 
* Message: "has been created."

##**Screen 4: Detailed Screen**
---
Editable Form with similar inputs as Screen 2

##Other Requirements
---
* System automatically sends e-mail to Creator & Assignee of that specific defect each time there is a change in that ticket
* Projects must exist before creating a ticket 