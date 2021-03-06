<h1>  post-It  </h1>


<h1></h1>

> Built with MERN stack (MongoDB, Express, React, and Node).
> post-It App, where you can post interesting facts,events that happened

## &nbsp; Table of contents

- [Introduction](#--introduction)
- [Main Features](#--main-features)
- [Setup](#--setup)
- [Demo](#--demo)
- [Technologies](#--technologies)
- [Key Concepts](#--key-concepts)


<h1></h1>

## &nbsp; Introduction

 Full Stack MERN Application - from start to finish. 

 The App is called "post-It" and it is a simple social media app that allows users to post interesting facts,events that happenes.
 
<h1></h1>


## &nbsp; Main Features


> This App was made to post user's interesting facts,news,events that happens in day to day life

>Users can like each others posts  



#### Project methodology

- **Product life cycle**
  - A user will post their memories through the form "Creating a post".
  - After posting the post will appear on the post-It section of the app.
  - From the post-It section of the app, all users of the app  will be able to see all the posts posted.  
  - Any user can like on the posts that are posted on the app.
  - Users can edit their previous posts by click on the post.
  - Users can add tags to their post.
  - Users can delete their respective posts.

<h1> </h1>

## &nbsp; Setup

- To run this project,  locally on your system
- Fork this repo and run the `git clone <forked repo>` command from your terminal/bash
- Create a `.env` file in the following  directory and store the following:
  - On server directory   
    - CONNECTION_URL=Insert the correct connection URL for your MongoDB database
  
```
$ cd  server 
$ npm install (install backend dependencies)
$ cd client
$ npm install (install frontend dependencies)
$ cd ..
$ cd sever
$ npm start (for Node server side development)
$ cd ..
$ cd client 
$ npm start (for React client side development)
```

- Backend server will be running on http://localhost:5000
- Frontend server will be running on http://localhost:3000

<h1></h1>


## &nbsp; Demo

<p align="center">
<p>Screenshoots of some main features</p>
<img src=./app-images/home1.png>
<p align="center">
  <img src=./app-images/home.png>
<p align="center">
  <img src="./app-images/responsive.png" width="200" height="356">
</p>
 <p align="center">
  <img src = "./app-images/post.png" width="300" height="402"> 
</p>
</p>
  

<h1></h1>

## &nbsp; Key Concepts

- CRUD operations
- Authentication system
- Storing user data
- OOP (Object Oriented Programming)

## &nbsp; Technologies

> Project is created with:

#### Backend

- Node Js : A asynchronous event-driven JavaScript runtime, Node.js is designed to build scalable network  applications. 
- Express : Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web applications.
- Mongoose : Mongoose is an Object Data Modeling (ODM) library for MongoDB and Node Js.
- MongoDB: MongoDB is a source-available cross-platform document-oriented database program. Classified as a NoSQL database program.
- JSON Web Tokens or JWTs : A JSON Web Token is used to send information that can be verified and trusted by means of a digital signature.

#### Frontend

- React JS:React JS  is a free and open-source front-end JavaScript library for building user interfaces or UI components.
- Redux :Redux is an open-source JavaScript library for managing application state.  
- React-Router : React Router is a  library for routing in React. It enables the navigation among views of various components in a React Application.
- Axios : Promise based HTTP client for the browser and node.js.
- Material UI : Material-UI is simply a library that allows us to import and use different components to create a user interface in our React Js.

