# Backend Documentation

This document provides an overview of the backend codebase. It includes information about the structure of the code, how to set up the development environment, and how to run tests.

## Table of Contents

- [Project Structure](#project-structure)
- [Environment Setup](#environment-setup)
- [Running Tests](#running-tests)
- [API Endpoints](#api-endpoints)
- [Error Handling](#error-handling)
- [Logging](#logging)

## Project Structure

The backend codebase is organized as follows:





- `controllers`: This directory contains all the controller files, which handle the business logic of the application.
- `models`: This directory contains all the data models used in the application.
- `routes`: This directory contains all the route definitions for the API.
- `tests`: This directory contains all the test files.
- `utils`: This directory contains utility functions and middleware.
- `server.js`: This is the entry point of the application.

## Environment Setup

To set up the development environment, follow these steps:

1. Clone the repository.
2. Install the dependencies with `npm install`.
3. Set up the environment variables in a `.env` file. Refer to `.env.example` for the required variables.
4. Start the server with `npm start`.

## Running Tests

To run the tests, use the command `npm test`.

## API Endpoints

The API provides the following endpoints:

- `GET /api/resource`: Retrieves a list of resources.
- `POST /api/resource`: Creates a new resource.
- `PUT /api/resource/:id`: Updates a resource.
- `DELETE /api/resource/:id`: Deletes a resource.

## Error Handling

Errors are handled by a middleware function in `utils/errorHandler.js`. This function sends a response with an appropriate status code and message.

## Logging

Logging is handled by a middleware function in `utils/logger.js`. This function logs all incoming requests and their responses.

Please refer to the inline comments in the code for more detailed information about each function and class.

