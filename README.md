
# RBAC System Implementation

This repository contains the implementation of a Role-Based Access Control (RBAC) system designed to manage user permissions efficiently within a web application. RBAC ensures that users can only access resources and perform actions based on their assigned roles, improving security and streamlining user management.


## Features

- **Dynamic Role Assignment:** Assign users to roles such as admin, manager, or user.
-** Permission Management:** Define granular permissions for each role to control access to specific actions or resources.
- **Secure Authentication:** Integration with a login system to ensure only authenticated users can access the application.
- **Customizable Roles:** Easily add, update, or remove roles based on application requirements.
- **Access Restrictions:** Implement middleware to enforce role-specific access across routes or actions.
- **Responsive Navigation**: Dynamic menu options displayed based on user roles.


## Tech Stack
**Node.js:** Backend server for handling requests and enforcing RBAC rules.

**Express.js:** Framework for building the web application and route handling. 

**MongoDB:** Database for storing user, role, and permission data.

**EJS:** Templating engine for rendering dynamic views.

**Bootstrap/HTML/CSS:** For responsive and user-friendly interface design.


## Installation

1.Clone the repository:

```
 https://github.com/NarendraSJ/Rbac.git
```
2. cd into the cloned repo and run:
```
npm install
```
3.Put your credentials in the .env file.
```
PORT=3000
MONGODB_URI=YOUR_MONGODB_URI(example: mongodb://localhost:27017)
DB_NAME=YOUR_DB_NAME
```
4.Run Mongo daemon
```
sudo service mongod start
```
5.Start the app by
```
npm start
```



