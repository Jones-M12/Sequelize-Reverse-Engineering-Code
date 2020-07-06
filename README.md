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
├── config
|   |
|   ├── middleware
|   |        └── isAuthenticated.js
|   |               └──> This file is used to direct the path of the user. If the use wishes to reached the member page they must be logged in or else they will be restricted from doing so |   |                     and wlll be directed to the login page.
│   ├── config.json
|   |       └──> ### Initiates the connection to MySQL..mmmm
│   └── passport.js
|
│ 
├── models
│   ├── index.js
│   └── user.js
│
│
├── public
│   ├── js
|   |    ├── login.js
|   |    ├── members.js
|   |    └── signup.js
|   |
|   |
│   ├── stylesheets
|   |     └── style.css
|   |
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



