# Go Practice Project: Movie API

This is a small practice project for Go, designed to learn Go programming and how to build a basic HTTP API using the Gorilla Mux router.

## Overview

This project creates a simple Movie API with basic CRUD (Create, Read, Update, Delete) operations. It demonstrates the following key concepts:

- Creating a RESTful API using the Gorilla Mux router.
- Structuring and defining data models.
- Handling HTTP requests and responses.
- Using JSON for data serialization.

## Features

The Movie API supports the following operations:

- **Get All Movies**: Retrieve a list of all movies.
- **Get Movie by ID**: Retrieve a specific movie by its ID.
- **Create Movie**: Add a new movie to the database.
- **Update Movie**: Update an existing movie by its ID.
- **Delete Movie**: Delete a movie by its ID.

## API Endpoints

- **GET /movies**: Retrieve all movies.
- **GET /movies/{id}**: Retrieve a specific movie by ID.
- **POST /movies**: Create a new movie.
- **PUT /movies/{id}**: Update an existing movie by ID.
- **DELETE /movies/{id}**: Delete a movie by ID.

## Data Model

- `Movie`: Represents a movie with fields `ID`, `Isbn`, `Title`, and `Director`.
- `Director`: Represents a movie director with `FirstName` and `LastName`.
