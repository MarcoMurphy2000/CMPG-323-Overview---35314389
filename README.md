# CMPG-323-Overview---35314389
## Repositories to be created and used for each project
This repository is for Project 1. <br />
All 5 Projects throughout this semester will each have their own reposirory tied back to one semester plan Kanban guide (Project).<br />
eg: <br />
Project 1: CMPG 323 - Overview <br />
Project 2: CMPG 323 - API Development <br />
Project 3: CMPG 323 - Standards & Patterns <br />
Project 4: CMPG 323 - Testing & RPA <br />
Project 5: CMPG 323 - Reporting & Monitoring <br />

## Project & Repository Structure
See diagram below: <br />
![image](https://user-images.githubusercontent.com/53267265/184188808-f01dd299-0169-4e7b-92ff-2ff9d6915332.png)

## Branching Strategy
Branching gives you an extra layer to do version control on, and allows you to maintain the integrity of your master branch. <br />
My branching strategy is the git flow branching strategy and can be seen in the diagram below.

![Git flow branching strategy](https://user-images.githubusercontent.com/53267265/184179834-49ff60a5-24e1-4de4-aafb-94077b6b89fb.png) <br />
Reference: [https://pbs.twimg.com/media/ExWjNqeVcAYWdYM?format=png&name=900x900 ](https://twitter.com/gitkraken/status/1375184717549539339)

I will isolate my work into 5 different branches to exercise flow control. <br />

✔️ Main <br />
✔️ Develop <br />
✔️ Feature <br />
✔️ Release <br />
✔️ Hotfit <br />

When working on a personal project it is not always necessary to have this many branshes. Once I start working on my other projects, I may decide to change this branching strategy; however, I intend to keep this branching strategy with the idea of preparing myself for the real world where I will be working in a team that requires employees to go through a procedure such as first working on a feature branch under the develop branch only having their work added to the main branch once it is production worthy.

## The use of a .gitnore file
The reason for a gitignore file is because there are certain items in your project that you don't necessarily want published to your repository.These items could be credentials or files giving access to your databases and so forth. <br />
You can exclude this sensitive data from your public repository by adding the path of the file that you want to ignore into the .gitnore text file.
Usually when using visual studio the .vs file should be added to the .gitnore file.

## The storage of credentials and sensitive information
Source code repositories are more often than not meant to be shared with either your teammates, your company or possibly the entire world. Therefore it is important not to place sensitive data such as database passwords and secret API keys directly in the source code. <br />

To avoid compromising sensitive data such as credentials, I wil store this data in a standalone file and gitnore the file.


## Project 2
Repository created<br />
Database Configured<br />
API project created<br />
API connected to data source<br />
Device, Zone, and Category management functionality built<br />
Security done
API connected to data source<br />
Device, Zone, and Category management functionality built<br />
Security done


## Project 3
* GitHub Administration: <br />
GitHub Repository created and configured. <br />
ReadME file created. <br />
Project Progress commited throughout the project. <br />

* Project Setup: <br />
Existing Repository forked and cloned to local machine. <br />
Development branch created. <br />
Web App connected to the data source. <br />

* Design Pattern Implementation: <br />
Repository classes created. <br />
Data access operations transfered from controllers to repository classes. <br />
Repository classes implemented. <br />

* Project Close out: <br />
Security Implemented (No credentials such as appsettings.json file stored on GitHub repository). <br />
Web API Cloud Hosting implemented. Project has been published to Azure resource group. <br />
Project Documentation implementation done. (ReadME file added in repository explaining how the user would use the App. ANd a complete reference list created. <br />

* Link to Project 3 repository: <br />
https://github.com/MarcoMurphy2000/CMPG-323-Project-3-35314389.git


## Project 4
* GitHub Administration: <br />
GitHub Repository for project 4 created and configured. <br />
ReadME file created. <br />
Project Progress commited throughout the project. <br />

* Project Setup: <br />
Connected Office Web App (link provided in project overview pdf) used for testing.  
UiPath Studio Installed. <br />
New UiPath process named 'Connected Office Web Application - User Acceptance Testing' created. <br />

* Design Pattern Implementation: <br />
Data read into data tables from excel. <br />
Mechanism that successfully tests the create & read functionality of all Zones test cases created. <br />
Mechanism that successfully tests the create & read functionality of all Devices test cases created. <br />
Mechanism that successfully tests the create & read functionality of all Categories test cases created. <br />
Mechanism that successfully tests the update & delete functionality of all Zones test cases created. <br />
Mechanism that successfully tests the update & delete functionality of all Devices test cases created. <br />
Mechanism that successfully tests the update & delete functionality of all Categories test cases created. <br />
Process hosted on the UiPath Orchestrator. <br />

* Project Close out: <br />
Security Implemented (No credentials such as appsettings.json file stored on GitHub repository). <br />
Project Documentation implementation done. (ReadME file added in repository explaining how the user would use the UiPath process. ANd a complete reference list created. <br />

* Link to Project 4 repository: <br />
https://github.com/MarcoMurphy2000/CMPG-323-Project-4---35314389.git  <br /> <br />



## Project 5 (Reporting & Monitoring)
* GitHub Administration: <br />
GitHub Repository for project 5 created and configured. <br />
ReadME file created. <br />
Development branch created. <br />
Solution has been committed and pushed to source control throughout the project. <br />
GitHub project has been updated iteratively throughout the project to demonstrate how progress was made. <br />

* Project Setup: <br />
Repostory for Project 4 cloned to local machine. <br />
Power BI Desktop installed. <br />
New Power BI report named 'Connected Office - Device Monitoring' created. <br />
Page named 'High-Level Metrics' created. <br />
Page named 'Device Monitoring' created. <br />
Page named 'Device Registration' created. <br />

* Data Connection: <br />
Live connection to the data sources that will be used as part of the visualisations created. <br />
Data sources secure, and appropriately mapped where necessary. <br />
Imported data fields are associated to the correct data types. <br />
At least one calculated column to enhance the quality of your dataset created. <br />
At least one key measure that will enhance the quality of your visualisations created. <br />

* Report Development: <br />
Summary view that shows business stakeholders a high-level view of the ‘important’ data added. <br />
Visual created that allows the user to monitor devices per category. <br />
Visual created that allows the user to monitor online versus offline devices (status should depict whether a device is online or offline). <br />
Visual created that allows the user to see how many devices have been registered over a timespan. <br />
Visual created that allows the user to see how many categories of devices have been created. <br/>
Visual created that allows the user to see how many zones contain registered devices on a timeline. <br />
Filter added for users to filter the report based on device category. <br />
Filter added for users to filter the report based on device platform. <br />
Filter added for users to filter the report based on device zone. <br />
Filter added for users to filter the report based on device registration date. <br />


* Project Close out: <br />
ReadMe.md file in the GitHub repository explains how the user would use the report. <br />
Reference list document created that contains all sites visited and used to complete the project. <br />

* Link to Project 5 repository: <br />

