# e-commerce-backend

## Description

This repository contains code for the backend of an E-Commerce website. In this code a database is created and populated with Categories, Products and Tags. There are API routes to view the Cateogires, Products and Tags all at once or by an individual ID. Additionally, there are API routes to Create, Update, and Delete anything for the Categories, Products or Tags. This repository utilizes Express.js, MySQL2, Sequelize, and dotenv packages.

---

## Table of contents

* [Installation](#installation)
* [Questions](#questions)

---

## Installation and How to Use

To install this project, download or clone the codebase from github. You will need to have Node.js and MySQL installed on your device as well. In the root directory of the project, find the ".env.EXAMPLE" file. Remove the ".EXAMPLE" from the name. Open up the .env file and input your MySQL Username, password, and ecommerce_db for the DB_NAME. Next, at the root directory run "npm install" to install the necessary packages. Now we need to setup the database, launch your mysql shell from the root directory of the project and run "source db/schema.sql" to create the ecommerce_db. Quit out of the MySQL shell after this is done. Then at the root directory of the project run "npm run seed" to seed the database. Finally, run "npm start" to launch the server. With the server now running you are able to execute any of the routes created to interact with the database. I used Insomnia for my purposes but this can simply be done in the browswer with the localhost. 

---

## Walkthrough Video
[How to use the application](https://drive.google.com/file/d/1RX4YYhL_BcV-3ZSPb-HDhqRCyegOTwpe/view?usp=sharing)

---

## Questions

If you have any questions about the project listed here or myself in general please contact me at alexdmarten@gmail.com. I will get back to you as soon as possible, thanks!

Interested in any of my other projects? Check out my github [alex-d-marten](https://github.com/alex-d-marten)

---