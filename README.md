# Unit 18 Nosql Homework: Workout Tracker

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

Project 18 tasked the student with building out the MVC parameters for a fitness workout logger that takes in new exercises and uses MongoDB with Mongoose to log them to the database which can then be analyzed in the app's dashboard that has multiple graphic views of the different workouts.
Completion of this app included the buidling out of the exercise model for the Mongo DB formatting to ensure the correct logging of the various fields in the application. As there are two different types of workouts avaialble, resistance and cardio, the requried fields for each of them will be the
same while there are a few fields that are only specific to the type of workout being logged.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [Contributing](#contributing)

## Installation

To install this application, first, branch the Github Repo and clone the repo to your local machine. Then, you will need to install the node dependencies which can be done by running the npm install command in your terminal/bash shell.

After the dependencies have been installed, you will need to populate your MongoDB database by uncommenting the required seed file or by running NPM Run Seed. Once filled in, you can start the server and use the program

## Usage

Once everything has been set up, the application can be launched by running the command node server.js or npm start. You will then need to visit the local host URL for the port that you have set up for this application. Once loaded in the browser, you can either click the dashboard page to view the
workout stats on the graphs provided or add/contnue a workout by clicking the buttons to add or update a new workout on the home page. When adding a new workout, ensure to click complete once you have filled everything in as if you click add exercise, then it will add a blank instance of a workout
with 0 for the numbers and no string for the title/name area.

## Credits

This application was completed by Andre Lucas for GW Full Stack Bootcamp.

Dependencies for this project include the node modules:

-Express: for setting up the node server

-Mongoose for setting up the models for MongoDB

-Morgan for adding the http request logger

## Contributing

If you would like to contribute to this application, please feel free to email me.
andre.lucas284@gmail.com

Link to Heroku app
https://sleepy-earth-68430.herokuapp.com/
