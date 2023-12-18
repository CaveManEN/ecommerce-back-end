# ecommerce back end

Welcome to the Express.js API with Sequelize! This project provides a functional API built using Express.js and Sequelize, allowing you to perform CRUD operations on a MySQL database. Follow the instructions below to set up and run the application successfully.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Database Configuration](#database-configuration)
- [Running the Application](#running-the-application)
- [API Routes](#api-routes)
- [Testing](#testing)

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- Node.js and npm (Node Package Manager)
- MySQL Database

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/express-sequelize-api.git
   ```

2. Navigate to the project directory:

   ```bash
   cd express-sequelize-api
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

## Database Configuration

1. Create a file named `.env` in the root of your project.

2. Add the following environment variables to the `.env` file, replacing the placeholders with your MySQL database details:

   ```env
   DB_NAME=your_database_name
   DB_USER=your_mysql_username
   DB_PASSWORD=your_mysql_password
   ```

## Running the Application

1. Run the following commands to create and seed the development database:

   ```bash
   npm run schema
   npm run seed
   ```

2. Start the application:

   ```bash
   npm start
   ```

3. Your server is now running, and Sequelize models are synced to the MySQL database.

## API Routes

### Categories

- **GET /api/categories:** Retrieve all categories in JSON format.

### Products

- **GET /api/products:** Retrieve all products in JSON format.

### Tags

- **GET /api/tags:** Retrieve all tags in JSON format.

### Testing

Use [Insomnia Core](https://insomnia.rest/download/) to test the API routes:

- Open Insomnia Core.
- Import the provided Insomnia workspace file (`insomnia_workspace.json`).
- Test the GET, POST, PUT, and DELETE routes for categories, products, and tags.

Congratulations! You have set up and tested the Express.js API with Sequelize. If you encounter any issues or have questions, feel free to reach out to the project contributors. Happy coding!
