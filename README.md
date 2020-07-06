# Notes Application

[![Generic badge](https://img.shields.io/badge/VERSION-1.1.0-PINK.svg)](https://shields.io/)

[Repo: Notes Application](https://github.com/Jones-M12/Notes-Application-Jones)

[Deployed Site: Notes Application Jones](https://notes-application-jones.herokuapp.com/)


## Overview

This application was designed to allow a user to utilize an online notes application for writing, saving and deleting notes. 

It allows a user to move away from hand written notes that can be lost or easily damaged.

A user can better organize ideas without forgetting or being unable to recall.

## Code Overview

I have designed this project from start to finish, gaining a better understanding of the importance of file stuctures, how they are connected, and how they cna help with organization.

You will see the file it setup similiar to the structure below:

style.css
```
.
├── config--> 📂 Folder contains configuration settings and middleware compotents that interact with the 
|   |              application to support verification metrics and route path direction.
|   |
|   ├── middleware
|   |        └── isAuthenticated.js
|   |               └──> ## This file is used to direct the path of the user. If the use wishes to reached the 
|   |                        member page they must be logged in or else they will be restricted from doing so                     
|   |                        and wlll be directed to the login page.
|   |
│   ├── config.json
|   |       └──> ## Initiates the connection to MySQL
|   |
│   └── passport.js
|           └──> ## Used to support confriguation and managing request for things like HTTP request for getting information
|                   and serving webpages related to an account. It defines the paramters the user must provide in order 
|                   to have access to the apllication, email and password conditions. Moreover, it confirms
|                   the existence of a user and assists with directing the route path accordingly.
│ 
├── models--> 📂 Folder contains dependencies that are used to create Sequelize tables.
|   |
│   ├── index.js
|   |       └──> ## provides the ability to allow all models within the models folders to be references when needed.
|   |
│   └── user.js
│          └──> ## Sequelize Model that represents a table.
|                  Note: Sequelize creates the table for us.
|                        Sequelize default, it will aito create a primary ID for each entry. Built in feature.
│
├── public--> 📂 Folder handles all clients side code.
|   |
│   ├── js--> # Folder handles the user interface interactions that process input to be used in conjuction with the server
|   |    |        to handle request.
|   |    |
|   |    ├── login.js
|   |    |      └──> ## Contains reference to dependencies that handle on click events for login, verifying account exist 
|   |    |              with email and password match. If correct, redirects user to the member page.
|   |    |
|   |    ├── members.js
|   |    |      └──> ## Verifies which user is logged in on based on the accouting formation that used to login, displaying 
|   |    |              the user welcome message or speicifc information relate to that user.
|   |    |              
|   |    └── signup.js
|   |           └──> ## Contains reference to dependencies that handle on click events for signing, verifying account does not
|   |                exist already. Successful sign up will redirects user to the member page. Else, user will be redirected to
|   |                the login page.
|   |
│   ├── stylesheets
|   |     └── style.css
|   |            └──> ## Handles page styling, the visual display seen by the client. If you still don't understand styling,
|   |                   check out [HTML & CSS Crash Course](https://scrimba.com/course/ghtmlcss)
|   |
|   ├── login.html
|   ├── members.html
│   └── signup.html
|
|
├── routes
│   ├── api-routes.js
│   └── html-routes.js
│
|
├── package.json
|   
│
└──server.js

```


## Contact Information

* Github: [Jones-M12](https://github.com/Jones-M12) 

* Email: malesharj@gmail.com 

* LindedIn: [m-jones89](https://www.linkedin.com/in/m-jones89/)



