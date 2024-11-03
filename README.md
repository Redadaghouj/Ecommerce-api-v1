# eCommerce API

A comprehensive REST API for eCommerce applications built with Node.js and Express, following best practices for scalability, security, and performance. This project provides essential functionality for managing products, orders, user authentication, and payments, using modern Node.js development practices.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)
- [License](#license)

## Overview
This project is a Node.js-based API designed to power eCommerce applications. It offers product, user, and order management, as well as integration with external payment gateways.

## Features
- **User Authentication**: User registration and login with JSON Web Tokens (JWT).
- **Product Management**: CRUD operations for managing product listings.
- **Order Management**: Cart and order processing with status updates.
- **Payment Integration**: Integration with payment gateways.
- **Role-Based Access Control**: Admin-level privileges for specific actions.
- **Data Validation**: Request data validation using middleware.

## Technologies Used
- **Node.js** - Server runtime environment
- **Express.js** - Web framework for Node.js
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling for Node.js
- **JWT** - Token-based authentication
- **bcrypt.js** - Password hashing

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Redadaghouj/Ecommerce-api-v1.git
   cd Ecommerce-api-v1
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## Configuration
1. Create a `.env` file in the root directory and include the following environment variables:
   ```plaintext
   PORT=not_available_yet
   MONGODB_URI=<not_available_yet>
   JWT_SECRET=<not_available_yet>
   ```

2. Configure other optional environment variables as needed.

## Usage
To run the API locally:
```bash
npm start
```

## API Documentation
### Authentication

### Products

### Orders

## Future Improvements

## License
This project is licensed under the MIT License.
