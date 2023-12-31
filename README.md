# API GraphQL Blog 🌐

Welcome to the Simple GraphQL Blog API project! This project serves as a basic example to showcase the implementation of a GraphQL API using Node.js and MongoDB. It also includes user authentication using JSON Web Tokens (JWT).

## Purpose 😉

This project is designed to provide a simple demonstration of how to set up a GraphQL API for managing a blog system. It covers essential concepts such as user registration, authentication, and creating blog posts through GraphQL mutations.

## Environment Variables 🤫

Before running the application, make sure to configure the following environment variables:

- 'MONGODB_URI': MongoDB connection URI
- 'PORT': Port number for the server to listen on
- 'JWT_SECRET': Secret key for JWT token generation and validation
- 'JWT_EXPIRES_IN': Expiration time for JWT tokens

You can set these variables in a '.env' file in the project root.

## Installation
```shell
npm i      # install dependencies
npm start  # run application
```