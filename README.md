# User Management Api 


"Welcome to the User Management Api  project! This application is a backend server built using Node.js and Express.js, designed to provide an API for managing places and users. With this server, you can perform CRUD operations on places, such as creating, retrieving, updating, and deleting places. Additionally, it allows you to manage users by registering new users, logging in existing users, and retrieving user information. The server utilizes MongoDB as the database to store and retrieve data efficiently. It provides a simple and intuitive API interface to interact with the backend services. Get started with User Management Api and streamline your place and user management process!"


## Table of Contents

- [Introduction](#introduction)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [License](#license)

## Introduction

This project aims to provide a [brief description of the project]. It implements a backend server using Node.js and Express.js, along with MongoDB for data storage. The server exposes various API endpoints to perform CRUD operations on places and users.

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
