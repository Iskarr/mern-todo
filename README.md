# mern-todo

This is a MongoDB, NodeJS, EJS, and Express Application that gives you the basic layout for both backend structure and provides you with simple requests that you can make to your own MongoDB collection. You will need to do some simple set up before you can run this application, it is not designed to work out of the box.

## Installation

You will need to download the project or clone it and go into the directory and run `npm install` to install the required dependancies.

## Setup

Once you install the dependancies, you will need to create a new `.env` file inside the root of the project and then include the following variables: <br />
`DATABASE_CONNECT="Your own mongodb connection string"` Don't forget your connection string will need a password and or login information to a root user that has access to your database.
<br />
`PORT=ADD-PORT-NUMBER-HERE` You will just add a port number of your choice right after the equal sign, no need to make it a string.
<br />
Create a .gitignore file that will include the following items when you upload your own project:
<br />
`node_modules`
`.env`
<br />
Once this setup has been done, you should be able to run `npm run start` to start up the server and load the applicaiton on the port of your choice.

## Code style

If you're using any code style like xo, standard etc. That will help others while contributing to your project. Ex. -

[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)

## Screenshots

![Screen Shot 2022-03-17 at 1 33 57 PM](https://user-images.githubusercontent.com/32428946/158881615-608693e4-7a6b-4cd0-99ff-32768a526e01.png)
<br />
You should have a project like this loaded up on your localhost of choice or on localhost:3000.

## Tech/framework used

<b>Built with</b>

- [MongoDB](https://www.mongodb.com/)
- [Express](https://expressjs.com/)
- [Nodejs](https://nodejs.org/en/)
- [EJS](https://ejs.co/)

## Features

Easy to use Todo Application built on the Express, Nodejs, EJS, and MongoDB frameworks and database.

## How to use?

Once you have followed all of the installation and setup instructions, open the terminal and use `npm run start` to run the project.

## Credits

Credit for the project goes to [Diogo Pinheiro](https://medium.com/@diogo.fg.pinheiro/simple-to-do-list-app-with-node-js-and-mongodb-chapter-1-c645c7a27583) for creating a tutorial to this project.
