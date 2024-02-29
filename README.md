# Task Manager

## Contents
[1. Description](https://github.com/richard-gotts/finalCapstone/edit/main/README.md#1-description)  
[2. Installation](https://github.com/richard-gotts/finalCapstone/edit/main/README.md#2-installation)  
[3. Instructions For Use](https://github.com/richard-gotts/finalCapstone/edit/main/README.md#3-instructions-for-use)  
[4. Credits](https://github.com/richard-gotts/finalCapstone/edit/main/README.md#4-credits)  

### 1. Description
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

### 2. Installation
To install the application, simply click on 'task_manager.py'. This will bring up the code for the program in GitHub. In the top right, click on 'Download raw file' and save the file in a location of your choice.

### 3. Instructions For Use
- In your IDE (e.g. Visual Studio Code), open the folder that you have saved the task manager in. It is important that you **always** have this folder open when using the task manager, as the program reads from and writes to text files that will be created and stored in this folder.

- Open the task manager and run the program. The first time you run the program, two text files will be created in the folder: 'tasks.txt' and 'user.txt'. **It is recommended that you do NOT open or edit these**, unless you want to delete a task or a user (see later).

- To login, use the username "admin", and the password "password". This will bring up a menu, giving you access to the functions in the program.

- If you want to delete a task, first exit the program. Then, open 'tasks.txt' and remove the single line containing the task in question. **Avoid making changes to any other tasks, as this could lead to them being read in incorrectly!**

- The same applies for deleting a user. **Avoid removing the line containing the admin login details** - an empty 'user.txt' file will prevent you from using the program!

- The 'generate reports' option will create two more text files in the folder: 'task_overview.txt' and 'user_overview.txt'. Each time you generate reports, these files will be overwritten with the current status of tasks managed by the program.


### 4. Credits
[HyperionDev](https://www.hyperiondev.com/): Existing features as outlined in '[1. Description](https://github.com/richard-gotts/finalCapstone/edit/main/README.md#1-description)'      
Richard Gotts: Updates as outlined in '[1. Description](https://github.com/richard-gotts/finalCapstone/edit/main/README.md#1-description)'
