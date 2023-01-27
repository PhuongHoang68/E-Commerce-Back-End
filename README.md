# ORM: E-commerce Back End


## What it is: 
A backend for an e-commerce website 

## Technologies used:
Built using Express.js, RESTful APIs, Sequelize with a MySQL database

## User Story
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Screen-recording of how this works:

[Ecommerce.webm](https://user-images.githubusercontent.com/109717048/209011850-2130c842-76cb-49a4-8b13-5151e63003f2.webm)


## How to install: 
First make sure node.js& MySQL are installed locally. Once the application is downloaded locally, create a .env file in your root folder. Include your password, your username, and the DB_NAME is "ecommerce_db". Be sure to run "npm i" followed by "npm run watch". 

## How to start:
You'll need to connect to the database, by the command "mysql -u(username) -p". It will ask for your password. After password input, run "source db/schema.sql". Exit the database from the command-line
Seed the database by typing "npm run seed"
You then start the server by running "npm start". Routes are now ready to be tested.

## Built by: 
Phuong Hoang. Contact at my email @p.hoang6897@yahoo.com
