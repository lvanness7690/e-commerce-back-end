# E-Commerce Back End

![Status](https://img.shields.io/badge/Status-Local%20API%20project-000000?style=for-the-badge)
![Stack](https://img.shields.io/badge/Stack-Express-000000?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-MySQL-000000?style=for-the-badge)
![Type](https://img.shields.io/badge/Type-REST%20API-000000?style=for-the-badge)

Express and Sequelize API for managing e-commerce data.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Links](#links)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Credits](#credits)
- [License](#license)

## Overview

A database-backed API for product, category, and tag management using Sequelize associations and RESTful routes.

## Features

- 🛍️ Product/category/tag models
- 🔁 REST API routes
- 🗃️ MySQL database
- 🔗 Sequelize associations
- 🌱 Seed data workflow

## Tech Stack

- JavaScript
- Node.js
- Express
- MySQL
- Sequelize
- dotenv

## Links

- Repository: [https://github.com/lvanness7690/e-commerce-back-end](https://github.com/lvanness7690/e-commerce-back-end)
- Live application: Not currently deployed. This repository is intended to run locally or serve as a code sample.

## Getting Started

1. `npm install`
2. `Create a MySQL database using db/schema.sql`
3. `Create a .env file with database credentials`
4. `npm run seed`
5. `npm start`

Common scripts:

- `npm run test`
- `npm run start`
- `npm run watch`
- `npm run seed`

## Usage

Run locally and test category, product, and tag routes with Insomnia or Postman.

## Project Structure

- `LICENSE.txt`
- `README.md`
- `config`
- `connection.js`
- `db`
- `models`
- `package-lock.json`
- `package.json`
- `routes`
- `seeds`
- `server.js`

## Credits

Developed and maintained by Leighton Van Ness.

## License

This project is licensed under the MIT license. See the license file in the repository for details.
