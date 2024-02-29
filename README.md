# Task Manager
  
  
## Contents
[1. Description](#1---description)  
[2. Installation](#2---installation)  
[3. Instructions For Use](#3---instructions-for-use)  
[4. Credits](#4---credits)  
  
  
### 1 - Description
This program is a task manager application which has been extended and refactored from an initial simple task management system.
  
#### Existing Features
- Login using username and password stored in .txt file
- Read in tasks from existing .txt file on startup
- Register a new user
- Add a task (username, title, description, due date, date assigned, completed)
- View all tasks
- View tasks assigned to current logged in user
- Display statistics (number of users and tasks)
  
#### Updates
- Existing functionality moved from main body to a set of functions, improving readability
- Issue of registering duplicate users fixed
- Option to edit tasks assigned to current user (mark as complete, reassign task, change due date)
- Functionality added to automatically update .txt file with these changes
- Option to generate task overview report with data regarding the status of tasks managed by the application
- Option to generate user overview report with data regarding allocation of tasks to users registered with the application and the status of tasks managed by application for each user
- Display statistics function modified to read in information directly from .txt files
- Control flow improved for better user experience
- Code checked for style consistency and descriptive variable names
- Thorough documentation added
  
  
### 2 - Installation
To install the application, simply click on 'task_manager.py'. This will bring up the code for the program in GitHub. In the top right, click on 'Download raw file' and save the file in a location of your choice.
  
  
### 3 - Instructions For Use
- In your IDE (e.g. Visual Studio Code), open the folder that you have saved the task manager in. It is important that you **always** have this folder open when using the task manager, as the program reads from and writes to text files that will be created and stored in this folder.

  ![ss1](https://github.com/richard-gotts/finalCapstone/assets/155302893/059c4dd9-9287-4fc6-848e-31721b407641)

- Open the task manager and run the program. The first time you run the program, two text files will be created in the folder: 'tasks.txt' and 'user.txt'. **It is recommended that you do NOT open or edit these**, unless you want to delete a task or a user (see later).

  ![ss2](https://github.com/richard-gotts/finalCapstone/assets/155302893/27eb4530-12f5-4ce8-9840-8b9208d2a54f)

- To login, use the username "admin", and the password "password". This will bring up a menu, giving you access to the functions in the program.

  ![ss3](https://github.com/richard-gotts/finalCapstone/assets/155302893/4f6ca70f-9273-498a-a450-707d6024ec36)

- If you want to delete a task, first exit the program. Then, open 'tasks.txt' and remove the single line containing the task in question. **Avoid making changes to any other tasks, as this could lead to them being read in incorrectly!**

  ![ss4](https://github.com/richard-gotts/finalCapstone/assets/155302893/7963aebc-8da2-4b6f-bd97-3cb774ea7b6a)
  
  ![ss5](https://github.com/richard-gotts/finalCapstone/assets/155302893/8149808d-ce2f-49fa-8f4b-ad033a988ce3)

- The same applies for deleting a user. **Avoid removing the line containing the admin login details** - an empty 'user.txt' file will prevent you from using the program!

- The 'generate reports' option will create two more text files in the folder: 'task_overview.txt' and 'user_overview.txt'. Each time you generate reports, these files will be overwritten with the current status of tasks managed by the program.

  ![ss6](https://github.com/richard-gotts/finalCapstone/assets/155302893/b4108c59-a561-4bb2-8127-2b3633d233f7)

  ![ss7](https://github.com/richard-gotts/finalCapstone/assets/155302893/616c6e2a-465e-4647-8f12-43c5803e6aee)

  ![ss8](https://github.com/richard-gotts/finalCapstone/assets/155302893/aa0fbe6e-2b2a-43d5-bad0-1756023c6bab)
  
  
### 4 - Credits
[HyperionDev](https://www.hyperiondev.com/): Existing features as outlined in '[1. Description](#1---description)'        
Richard Gotts: Updates as outlined in '[1. Description](#1---description)'
