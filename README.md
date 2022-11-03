# Frello - Project management app inspired by trello.com

[Here's a link to my project](https://frello-urbc.onrender.com/ "Frello link").

![Main board image](https://res.cloudinary.com/frello/image/upload/v1667464170/j5dtjwbvzxjz2lvzybv3.png "Board-main-page")

___

### Table of Contents
- [Trello Description](#trello-description)
- [Application Features](#application-features)
- [Technologies](#technologies)
- [Getting started](#getting-started)
- [Showcase](#showcase)

## Trello Description
Trello is an app in which you can manage projects and tasks using a kanban board. A board contains lists and tasks. Usually each project is a board, and the lists and cards are the tasks and subjects to do in the project. Users can modify the board and change list and card locations using Drag and Drop.
Users can work together and watch live changes. 
There are many other features in Trello, such as labels, due date for tasks, members and more. 

## Application Features
- ***Boards*** - Create and manage projects: Using ***D&D***, create, remove, and update lists and tasks.
- ***Tasks*** - Create, edit and delete to the deepest level: labels, due date, members, cover images, checklists, locations, attachments, activity log, comments, move and delete.
- ***Filtering*** - Filter tasks based on title, members assigned to the task and labels.
- ***Side Menu*** - Change the background of the board with the ***Unsplash Photo API*** and a full board ***Activity Log***!
- ***Google Login*** - along with regular authentication which is encrypted and safe.
 
We spent a lot of effort on making sure that the app is as close as possible to the original trello both in design and in functionality.

## Technologies

The technology stack we used was MERN - MongoDB, Express, React, Node.js.
The app uses webSockets to update the board in real-time.
The API calls to the backend are done with the REST API method.

We have used many third side libraries for many goals, such as google-login, D&D, Unsplash and more.
The layout and pixel-perfect were made with Sass (functions, mixins, variables). 

## Getting started

Head to the repositories 'frello-frontend' and 'frello-backend' in my profile and clone the project or download the files.

```
git clone https://github.com/YasminGd/frello-frontend.git
```

```
git clone https://github.com/YasminGd/frello-backend.git
```

Enter the backend part of the project and make sure you have node_modules installed. After that we will initiate the server with 'npm start':

```
npm i 
npm start
```

You shuold get a console output that the server is up and running at port 3030.
Enter the frontend section of the project and repeat the same process.

```
npm i 
npm start
```

You shuold get a console output that that the server is up and running at localhost:3000.

That's it! The App should open automatically, enjoy!

## Showcase

### Homepage
The landing page in which the user can sign up / login, or press the call to action button to start a demo with no need for registration.

![Homepage image](https://res.cloudinary.com/frello/image/upload/v1667464161/gyxllhvyxjssir0gc1p2.png "Home-page")

### Workspace
All of the user's boards. Here the user can create new boards and visit existing ones.

![Workspace image](https://res.cloudinary.com/frello/image/upload/v1667464151/igezrmnx0hgi3riuiv94.png "Workspace-page")

### Board
All the functionality that you have in Trello. D&D, live-updates, editing tasks to the deepest level, side-menu, editing board members and much more - just [check it out...!](https://frello-urbc.onrender.com/ "Frello link")

![Main board image](https://res.cloudinary.com/frello/image/upload/v1667464170/j5dtjwbvzxjz2lvzybv3.png "Board-main-page")

### Signup
We created a sign up system that uses ***Google Login***.

![Login image](https://res.cloudinary.com/frello/image/upload/v1667464229/k18oqfapuylkysdok2bd.png "sign-up-page")

### Task details
Here the user can edit his tasks and watch it happens live, on this page and behind it, on the board. Every button on the right menu opens a dynamic modal which fits his position accordingly to the pressed button.

![Task details image](https://res.cloudinary.com/frello/image/upload/v1667464196/fkof2kzi6kv2fkwriotu.png "task-details")


### Side menu
The menu on the right which is opened by pressing the "Show menu" button enables the user to change the board's background with unsplash Images and watch the activities of the board.

<p align="center">
  <img src="https://res.cloudinary.com/frello/image/upload/v1667464206/xrdqf372yp68lcxjp7kp.png" width="45%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img src="https://res.cloudinary.com/frello/image/upload/v1667464220/mpk7xau42fvwwaebokg7.png" width="45%">
</p>

### Some mobile!
Just a taste of the mobile experience. We used different **mixins**, **conditional rendering** and the **"mobile first"** approach. 

<p align="center">
<img src="https://res.cloudinary.com/frello/image/upload/v1667464191/r96utiiatbizpbxpm4fj.png" width="24%" /><img src="https://res.cloudinary.com/frello/image/upload/v1667464184/wv1o07jmwpumgxsgi0eh.png" width="24%" />
<img src="https://res.cloudinary.com/frello/image/upload/v1667464177/d7dwaizxasu00b18eudx.png" width="24%" /><img src="https://res.cloudinary.com/frello/image/upload/v1667464196/fkof2kzi6kv2fkwriotu.png" width="24%" />
</p>

### Authors
 - [Yasmin Gudha](https://github.com/YasminGd)
 - [Bar Ohayon](https://github.com/OhayoNB)
 - [Lee Sharon](https://github.com/leesharon)
