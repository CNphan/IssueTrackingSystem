
**Table Of Contents**

[toc]
##Introduction##

----------
This is a personal project that I am working on. It is an issue tracking system that allows managers to manage the status of a task. 

## Requirements##

----------

The feature requirements of the project are listed below in different screens. 
### Screen 1: List of Open Defects (Tickets) - Default Screen
---
* Defect name 
* Summary 
* Assignee 
* Split Screen or Bootstrap Modal on single Defect ( Update Information)
* Create Button: Creates the ticket - Link to Screen 2 

### Screen 2: Ticket Submission Screen
---
* Project Name : Drop-down -must exist in DB
* Defect Name : pre-pop (incremental with unique identifier)
* Summary 
* Status : Open (Default), In-Progress, Closed 
* Priority: Drop-down :: Low, Medium, High 
* Assignee: Select from existing 
* Description 

###Screen 3: Ticket Submission Modal
---
* Defect Name 
* Summary 
* Message: "has been created."

###Screen 4: Detailed Screen
---
Editable Form with similar inputs as Screen 2

###Other Requirements
---
* System automatically sends e-mail to Creator & Assignee of that specific defect each time there is a change in that ticket
* Projects must exist before creating a ticket 

## Environment##

----------

###Development Environment 
####Front-End System
Fron-End technologies -- In progress 

**HTML5**
 - W3School | http://www.w3schools.com/html/
 - TutorialPoint | http://www.tutorialspoint.com/html/
 
**CSS3**
 - W3School | http://www.w3schools.com/css/default.asp
 - TutorialPoint | http://www.tutorialspoint.com/css/
 
**JavaScript**
- W3School | http://www.w3schools.com/js/default.asp
- TutorialPoint | http://www.tutorialspoint.com/javascript/

**JQuery**
- Get JQuery | https://jquery.com/
- W3School | http://www.w3schools.com/jquery/default.asp
- TutorialPoint | http://www.tutorialspoint.com/jquery/

**Bootstrap**
- Get Boostrap | http://getbootstrap.com/ 
- W3School | http://www.w3schools.com/bootstrap/default.asp
- TutorialPoint | http://www.tutorialspoint.com/bootstrap/

####Back-End System
Backend development is under construction - I am still thinking about what system to use. Most likely, it will be Node.js and either MySQL or MongoDB

**Node.js**
 - Get Node.js | https://nodejs.org/en/
 - TutorialPoint | http://www.tutorialspoint.com/nodejs/

###End User Environment 
**Web Browsers**

###Development Tools 
You can use any standard text editor to develop your application. You will also need to configure the development environment using Command Line. Recommendations are listed below. 

**Text Editor**

 - Sublime Text Editor | https://www.sublimetext.com/
 - Brackets.io | http://brackets.io/
 - Ataom.io | https://atom.io/
 - Webstorm | https://www.jetbrains.com/webstorm/
 - Cloud9.io | https://c9.io/ 

**Command Line**

 - Tutorials : https://www.codecademy.com/learn/learn-the-command-line
 - Mac OS | Terminal 
 - Windows OS | https://www.cygwin.com/  OR DOS
 - Linux OS | Terminal 

## Data Models ##
Pending...

----------


> Written with [StackEdit](https://stackedit.io/).