# E-commerce__Backend
homework 13


# Objective

The goal of this assignment is to gain a deeper understanding for Object-Relational Mapping through data management with complex applications. ORM make data more manageable by using JavaScript to interact across databases, migrate existing data, and use several different type of databases. 

This application utilizes Sequelize as the main database. 


## Installation & Usage

This project uses Node.JS as well as a collection of other packages including sequelize and mysql2, featured in the package-json. To install the packages type in your terminal `npm i`.

Create an `.env` file to store user information for SQL connection set up like the following:

```md
DB_NAME=''
DB_USER=''
DB_PW=''
```
Once installing the packages and setting up your `.env` file, navigate to your gitbash terminal and enter `mysql -u root -p` to access the mysql shell command line. 

Within the mysql shell command you will need to enter `source db/schema.sql` to set up the database. You will then type `quit` and then enter within the gitbash terminal `npm run seed` to seed the database you just created

To run the program type in your console `nodemon server.js` to run the program.

You will then have your server live and can open up the Insomnia app to test out different `GET` , `POST` , `PUT` , and  `DELETE` paths.

Note: Program is ran through viewing in insomnia, mysql shell,  and the Gitbash terminal within Visual Studio Code.


## Links

- [Video Walkthrough](https://drive.google.com/file/d/1ddQs32St55RbSfsxjZzQK3VUM6mfRbpn/view)


