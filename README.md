# GP2 TODO APP TEST --> MIGHT USE THIS FINALLY
### ⚡ TODO APP
A to-do app is a digital tool that helps you organize and manage your tasks, projects, and daily responsibilities. It allows you to create and prioritize a list of things you need to do, set reminders, and track your progress. You can also use a to-do app to assign tasks to others, share lists, and collaborate with team members. Overall, a to-do app is a helpful tool for individuals and teams to stay organized and productive.

--> FOR READING https://github.com/topics/django-todoapp

### ⚡ GROUP MEMBERS
 Here are the members of Group 2 as of today
 
|🔸| RONALD ATUHAIRE	| 22/U/3003/EVE	| 2200703003 |
| ------ |------ | ------ | ------ |
|🔸|EDWARD KABOGGOZA | 22/U/20894/EVE	 | 2200720894 |
|🔸|ARIHO GERALD   	 |22/U/21723/PS	   |2200721723  |
|🔸|SSEMAGANDA GEORGE|	   22/U/3847/EVE| 2200703847 |

### ⚡ PROJECT SUMMARY _ OUR UNDERSTANDING
Based on the given requirements, the project is to develop a to-do application using the Django framework for the back-end and JavaScript, HTML, and CSS for the front-end. The application should allow users to create and manage daily or weekly lists of tasks, mark tasks as completed or skipped, and set reminders for specific tasks via email notifications. The application should also allow users to delete tasks and automatically remove tasks older than seven days.

In terms of user stories, the project can be broken down into several stories including user account creation, task creation and management, task completion and skipping, task reminders, task deletion, and task auto-removal. Each story can be further broken down into implementation tasks such as creating database models, building user interfaces, implementing email notifications, and configuring deployment settings.

To implement this project, an agile software development framework such as Extreme Programming (XP) will be used. The development team will work collaboratively to prioritize user stories, estimate and plan implementation tasks, conduct iterative development, and continuously test and deploy the application.

The development process will be divided into sprints, each lasting approximately one to two weeks, with each sprint focusing on delivering a set of user stories. The project plan will be updated after each sprint to reflect progress made, issues encountered, and any changes to the scope or timeline.

Overall, the project aims to deliver a user-friendly and functional to-do application that meets the given requirements and adheres to best practices for software development.

### ⚡ DEFINED APP PARAMETERS
In this project, we shall create a To Do App with the following parameters as set by Dr. Peter W in project submission.<br>
- [ ] *The app should allow the user to create and manage a list of tasks.*<br>
- [ ] *The user should be able to create daily or weekly lists of tasks.*<br>
- [ ] *The app should require the user to set up an account before creating tasks.*<br>
- [ ] *The app should provide a way for the user to keep track of completed tasks.*<br>
- [ ] *The user should be able to mark tasks as "completed" and update their to-do list.*<br>
- [ ] *The app should allow the user to specify the expected date and time of each task.*<br>
- [ ] *The user should be able to set reminders for tasks, and specify the time of the reminder in minutes.*<br>
- [ ] *The app should send reminders via email to the user, containing a link to the task.*<br>
- [ ] *Tasks that are incomplete but whose time has passed should be marked as "skipped".*<br>
- [ ] *The user should be able to delete tasks.*<br>
- [ ] *The app should automatically delete all tasks that are older than seven days.*<br>
- [ ] *The app should use either PostgreSQL or MySQL as a database

### ⚡ TECH & COSTRAINTS
The To Do App is going to have or use the following technologies and constraints:

- The back-end system of the to-do app should be developed using the Django framework.
- The front-end system should be built using tools like JavaScript, HTML, and CSS.
- The app should have a minimal user interface design.
- The app should be deployed on an online server using Django/Flask framework.
- The app should be developed using the Extreme Programming (XP) methodology.
- The app should aim to produce higher quality software and higher quality of life for the team.
- The app should be fully functional and meet the requirements outlined in the planning and design phase.
- The app should be thoroughly tested to ensure it is free of bugs and errors.
- The app should be easy to use and intuitive for the end-user.
- Use of Restful API and methadology.
- Front end and backend should be called by the above methadology (Loosely coupled).
- Use of a database (PostgreSQL or MySQL)
- The code for the app should be well-organized, efficient, and maintainable.


### ⚡ USER STORIES
User stories are a way of defining user requirements in the form of a short, simple statement of what a user wants to accomplish. Based on the requirements mentioned in the text, some possible user stories for a to-do app are:

🔸 As a user, they would want to see a landing page about the app with the ability to signup or signin. <br>
**Tasks:**
- Design a beautiful UI/UX with a good landing page.
- Ability to have account creation and sign in buttons or validation forms
- Validate input from the users and account signups
- Send account confirmations


🔸 As a user, I want to be able to create a list of tasks that I need to complete. <br>
**Tasks:**
- Design the user interface to allow users to create a new task.
- Implement a view to add a new task to the database.
- Write a form validation function to validate user input.


🔸 As a user, I want to be able to mark a task as completed.<br>
**Tasks:**
- Add a "completed" field to the task model.
- Design the user interface to allow users to mark a task as completed.
- Implement a view to update the completed field of a task in the database.


As a user, I want to be able to specify the expected date and time of each task.
Tasks:
Add "date" and "time" fields to the task model.
Design the user interface to allow users to enter the date and time of a task.
Implement a view to add the date and time fields to a task in the database.
As a user, I want to be reminded of a task when it's due.
Tasks:
Write a function to check if any tasks are due and send a reminder email.
Add a "remind" field to the task model.
Design the user interface to allow users to set a reminder for a task.
Implement a view to add the remind field to a task in the database.
As a user, I want to be able to delete a task.
Tasks:
Design the user interface to allow users to delete a task.
Implement a view to delete a task from the database.
As a user, I want tasks that are incomplete but whose time has passed to be marked as skipped.
Tasks:
Write a function to check if any tasks have passed their due date and mark them as skipped in the database.
Based on these user stories, the order in which the stories will be implemented can be as follows:

As a user, I want to be able to create a list of tasks that I need to complete.
As a user, I want to be able to mark a task as completed.
As a user, I want to be able to specify the expected date and time of each task.
As a user, I want to be reminded of a task when it's due.
As a user, I want to be able to delete a task.
As a user, I want tasks that are incomplete but whose time has passed to be marked as skipped.


### ⚡ PERSONAL GIT ACCOUNTS
Here are the indiviual Git Accounts for every person that worked on the project.

|🔸| ACOUNT HOLDER'S NAME |GIT USER NAME |
| ------ |------ | ------ | 
|🔹 |RONALD ATUHAIRE | [Ronlin1](https://github.com/Ronlin1) 
|🔹 |EDWARD KABOGGOZA |GITHUB ACCOUNT <br>
|🔹 |ARIHO GERALD |GITHUB ACCOUNT <br>
|🔹 |SSEMAGANDA GEORGE| GITHUB ACCOUNT <br>

### ⚡ CI/CD & DELIVERABLE TIMELINES
The following are the deadlines for the different delivereables that will be updated with time:
- [x] Deliverable 1: Date Due: 9th March 2023 <br>
- [ ] Deliverable 2: 26th April 2023 <br>
- [ ] Deliverable 3: 31st May 2023 <br>

on it


### ⚡ ONLINE DEMO
~~Please visit this for online demo. (url incoming)~~

### ⚡ HOW TO RUN THE APP LOCALLY
After full project: The following commands and instructions will be used to deploy and run our To-Do App locally.
- Clone the repository:<br>
``` git clone <repository_url> ```
- Install project requirements: <br>
``` pip install -r requirements.txt ```
- Migrate the database:<br>
``` python manage.py migrate ```
- Start the development server:<br>
``` python manage.py runserver ```
- Access the app:<br>
Go to the URL ```http://localhost:8000/``` to access the app. 

The port number might be different if you have specified a different port in the runserver command.

### ⚡ MORE INFORMATION
This is the current information that is due to change about this repo but more information can be got from the Group Leader: **Eddy on 0705044294**

## 🙆‍♀😍 TEAM MEMBERS & PROJECT ROLES
|Ronnie A<br/>([@Ronnie](https://github.com/Ronlin1))|Edward<br/>([@Edward](https://github.com/Ronlin1))|Gerald M<br/>([@Gerald](https://github.com/Ronlin1))|George<br/>([@George](https://github.com/Ronlin1))|
|:----------:|:----------:|:----------:|:----------:|
|FRONT DEV<br/>DEV|Developer<br/>UI/UX|FRONT DEV<br/> Systems Mgr |Project Manager<br/>Dev-Ops|
|![](https://github.com/Ronlin1.png)|![](https://github.com/Ronlin1.png)|![](https://github.com/Ronlin1.png)|![](https://github.com/Ronlin1.png)|


<br/><br/>
