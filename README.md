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

When working on a personal project it is not always necessary to have this many branshes. Once I start working on my other projects, I may decide to change this branching strategy; however, I intend to keep this branching strategy with the idea of preparing myself for the real world where I will be working in a team that requires many branches before being able to push work directly to the main (production) branch. 

## The use of a .gitnore file
The reason for a gitignore file is because there are certain items in your project that you don't necessarily want published to your repository.These items could be credentials or files giving access to your databases and so forth. 
You can exclude this sensitive data from your public repository by adding the path of the file that you want to ignore into the .gitnore text file.
Usually when using visual studio the .vs file should be added to the .gitnore file.

## The storage of credentials and sensitive information
Source code repositories are more often than not meant to be shared with either your teammates, your company or possibly the entire world. Therefore it is important not to place sensitive data such as database passwords and secret API keys directly in the source code. To avoid compromising these secrets, rather store them in a standalone file and gitnore the file.
