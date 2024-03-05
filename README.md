# E-Commerce Back-End

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

## Usage

After installation, run the application with `npm start`. The application provides various routes to manage categories, products, and tags within the e-commerce database. You can:

- View all categories, products, and tags
- Add a new category, product, or tag
- Update an existing category, product, or tag
- Delete a category, product, or tag

Navigate through the routes using tools like Insomnia Core or Postman to interact with the backend database efficiently.

## Credits

Developed by [Your Name].

## License

This project is licensed under the [MIT License](LICENSE.txt).

---

## Features

- Sequelize ORM for interacting with MySQL database
- Express.js for handling HTTP requests
- CRUD operations for categories, products, and tags
- Scalable backend infrastructure for an e-commerce website

## How to Contribute

Contributions are welcome! If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

If you find any bugs or issues, please report them [here](https://github.com/lvanness7690/e-commerce-back-end/issues).
