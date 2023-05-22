# User Management Api 

## Table of Contents

- [Introduction](#introduction)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [License](#license)

## Introduction

This project is a backend server implementation that provides a RESTful API for managing places and users. It is built using Node.js and Express.js, with MongoDB as the database for storing and retrieving data. The server allows users to create, read, update, and delete places, as well as register and authenticate users.

The main features of this project include:

- CRUD operations for managing places, including creating new places, retrieving places by ID or associated user ID, updating place details, and deleting places.
- User registration and login functionality, with secure password hashing and authentication using JSON Web Tokens (JWT).
- Integration with MongoDB for persistent data storage and retrieval.
- Error handling and appropriate HTTP status codes for API responses.
- Input validation and data sanitization using Express.js middleware.

This project serves as a foundation for building applications that require backend functionality for managing places and user authentication. The provided code consists of the server setup, routing, controllers for handling API requests, and the necessary models for working with the data.

Feel free to explore the code and customize it according to your specific requirements and project needs.


## Technologies

- Node.js
- Express.js
- MongoDB
- Mongoose

## Installation

To run this project locally, follow these steps:

1. Clone the repository: `git clone <repository-url>`
2. Navigate to the project directory: `cd <project-folder>`
3. Install the dependencies: `npm install`

## Usage

To start the server, use the following command:

npm start


Make sure you have a running MongoDB server and update the connection string in `app.js` to match your MongoDB configuration.


## Dependencies

The project has the following dependencies:

- express: Fast, unopinionated, minimalist web framework for Node.js.
- body-parser: Node.js body parsing middleware.
- mongoose: MongoDB object modeling tool designed to work in an asynchronous environment.
- express-validator: A set of express.js middlewares that wraps validator.js validator and sanitizer functions.
- uuid: Generate RFC-compliant UUIDs.


## API Endpoints

The server exposes the following API endpoints:

- `GET /api/places/:pid`: Retrieves a specific place by ID.
- `GET /api/places/user/:uid`: Retrieves all places associated with a specific user.
- `POST /api/places`: Creates a new place.
- `PATCH /api/places/:pid`: Updates a specific place by ID.
- `DELETE /api/places/:pid`: Deletes a specific place by ID.
- `GET /api/users`: Retrieves all users.
- `POST /api/users/signup`: Registers a new user.
- `POST /api/users/login`: Logs in an existing user.

For detailed information on request and response formats, please refer to the corresponding route files in the `routes` directory.


## Contributing

Contributions to this project are welcome. To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit your changes and push them to your forked repository.
5. Create a pull request detailing your changes.



Ali OZZAIM
