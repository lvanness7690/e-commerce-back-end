# E-Commerce Back-End
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents\
* [Description](#description)
* [Installation](#installation)
* [Technologies Used](#technologies-used)
* [Application Demo](#application-demo)
* [Usage](#usage)
* [Features](#features)
* [Credits](#credits)
* [License](#license)

## Description

The E-Commerce Back-End is a Node.js application designed to manage the backend database of an e-commerce website. It utilizes Sequelize ORM, Express.js, and MySQL to provide a robust backend infrastructure. With this application, users can interact with the database to manage categories, products, and tags efficiently.

## Installation

To install the E-Commerce Back-End, follow these steps:

1. Clone the repository to your local machine.
2. Run `npm install` to install all the necessary dependencies.
3. Ensure you have MySQL installed and running on your local machine.
4. Set up your MySQL database using the schema provided in the `db/schema.sql` file.
5. Optionally, you can populate your database with initial data using the `db/seeds.sql` file.
6. Create a `.env` file in the root directory and fill in your MySQL credentials, following the example provided in the `.env.EXAMPLE` file.
7. Run `npm start` to start the application.

## Technologies Used

This application is powered by Node.js (v16.19.1), Express.js (v14.17.1), JavaScript, MySQL, and Sequelize (ORM). It utilizes the node package manager (npm) dependencies sequelize (v5.22.5), mysql2 (v2.3.3), express (v4.17.1), dotenv (v8.6.0), and nodemon (v2.0.3). Also, the Insomnia application was utilized to test the functionality of routes within the program.

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white)
![Nodemon](https://img.shields.io/badge/NODEMON-%23323330.svg?style=for-the-badge&logo=nodemon&logoColor=%BBDEAD)
![Insomnia](https://img.shields.io/badge/Insomnia-black?style=for-the-badge&logo=insomnia&logoColor=5849BE)

## Application Demo

[Professional README Generator Demo Video](https://www.icloud.com/iclouddrive/065dvp9pS-iL4DT-YO0U7HQvQ#E-Commerce-Back-End_Demo)

## Usage

After installation, run the application with `npm start`. The application provides various routes to manage categories, products, and tags within the e-commerce database. You can:

- View all categories, products, and tags
- Add a new category, product, or tag
- Update an existing category, product, or tag
- Delete a category, product, or tag

Navigate through the routes using tools like Insomnia Core or Postman to interact with the backend database efficiently.

## Features

- Sequelize ORM for interacting with MySQL database
- Express.js for handling HTTP requests
- CRUD operations for categories, products, and tags
- Scalable backend infrastructure for an e-commerce website

## Credits

Developed by Leighton Van Ness with starter code from Columbia EDx Bootcamp

## License

Please refer to the license in the repo.
