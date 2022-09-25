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
* GitHub Administration
GitHub Repository created and configured. <br />
ReadME file created. <br />
Project Progress commited throughout the project. <br />

* Project Setup
Existing Repository forked and cloned to local disk. <br />
Web App connected to the data source. <br />

* Design Pattern Implementation
Repository classes created. <br />
Data access operations transfered from controllers to repository classes. <br />
Repository classes implemented. <br />

* roject Close out
Security Implemented (No credentials such as appsettings.json file stored on GitHub repository). <br />
Web API Cloud Hosting implemented. Project has been published to Azure resource group. <br />
Project Documentation implementation done. (ReadME file added in repository explaining how the user would use the App. ANd a complete reference list created. <br />





