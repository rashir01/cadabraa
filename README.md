# Cadabraa: E-Commerce Back End

## Description

This is an internet ecommerce site prototype. It is used to show the design of a mock ecommerce site that links products to tags to categories. 

In this project you will see demos of users being able to make modification, delete, and view items stored in DB using API routes. 

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
----DONE by just update the ENV file----

WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
----DONE----

WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
----done----

WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```

## Mock-Up

The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia Core:

[In Insomnia Core, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](https://drive.google.com/file/d/1Iqj4O9fkqUi1HX1BVv_5DQlQ2n8olGl5/view?usp=sharing)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia Core:

[In Insomnia Core, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](https://drive.google.com/file/d/1DBKDQmFlnqua-VZLWqsHgWWzlG8r7MmO/view?usp=sharing)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia Core:

[In Insomnia Core, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](https://drive.google.com/file/d/1aWm6NTwzZKAJrnUpe8y4Shd60O7XzImb/view?usp=sharing)

[Insomnia POST, PUT, DELETE for products](https://drive.google.com/file/d/1pc5Nehtcd4rEoC8fmShPeTkB_a8Pi91u/view?usp=sharing)

[Insomnia POST, PUT, DELTE for tags](https://drive.google.com/file/d/1PkZiJ66uF_CEKdc3v3-DYr0yUEPQ8UI7/view?usp=sharing)

[db seed demo](https://drive.google.com/file/d/1kobL_U1323nhKjt2Mg51Zbe3zcmQnlnB/view?usp=sharing)

[db install demo](https://drive.google.com/file/d/1RlTKvLipetWNjoN2FRFTKy38RCZ5pCsb/view?usp=sharing)


## Getting Started

run npm install  

run npm start

set up database 

run the seeds to add data to db

use insomina to hit run the APIs



### Seed the Database

After creating the models and routes, run `npm run seed` to seed data to your database so that you can test your routes.

### Sync Sequelize to the Database on Server Start

Create the code needed in `server.js` to sync the Sequelize models to the MySQL database on server start.

## Links

You are required to submit BOTH of the following for review:

[Git hub link]()

---
© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
