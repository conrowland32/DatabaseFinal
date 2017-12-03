# Database Final Project
### Members
* Logan Harrison
* Connor Rowland
* Joe Wong

### Application Description
This project is a web app to help users manage their contacts. First, a user logs in and makes an account. Once the account is created, they will login and see their dashboard. This dashboard will be where all contacts are displayed. In the bottom right there is a "+" button that allows users to add contacts. A new popup will be displayed that has all of the fields that a user can fill out to add a contact. Once contacts are added, they will display on the dashboard, as well as the option to edit and delete each contact. By clicking on the headers at the top of the table, the user's contacts will be sorted (ascending or descending) by that column. 

### CRUD
There are two main entities in our app: users and contacts. Users do not have full CRUD capabilities, but the contacts users create support full CRUD capabilites.
##### Create
Contacts are created by pushing the "+" button in the bottom right of the dashboard and then completing the accompanying form. The actual creation happens on line 162 of `server.js`.
##### Read
Contacts are read and displayed on the contacts dashboard page. The functionality to read all the contacts for a given user from the database is done on line 259 of `server.js`.
##### Update
Contacts can be updated by clicking the yellow pencil on the contacts dashboard. This functionality is on line 326 of `server.js`.
##### Delete
Contacts can be deleted by clicking the red trash can on the conacts dashboard. The deletion from the table is performed on line 355 of `server.js`.

### Website
[Link to website](http://ec2-52-72-121-61.compute-1.amazonaws.com:3000)

### Video Demo
[Link to video](https://youtu.be/pqNncVIm2Ls)
