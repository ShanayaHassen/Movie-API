# 🎬 Movie API

A RESTful Movie API built to manage movie-related data using CRUD (Create, Read, Update, Delete) operations. This project demonstrates backend development concepts such as REST APIs, database integration, and layered architecture.

## Features

* Create a new movie
* Retrieve movie details
* Update existing movies
* Delete movies
* RESTful API design
* Database integration

## Tech Stack

* Java
* Spring Boot
* Maven
* MongoDB
* Spring Data MongoDB

## Getting Started

### Prerequisites

* Java 21 or later
* Maven
* MongoDB

### Clone the Repository

```bash
git clone https://github.com/ShanayaHassen/Movie-API.git
cd Movie-API
```

### Configure the Database

Update your MongoDB connection details in the application configuration or set the required environment variables.

### Run the Application

```bash
./mvnw spring-boot:run
```

or

```bash
mvn spring-boot:run
```

The application will start on:

```
http://localhost:8080
```

## API

The API provides REST endpoints for managing movie data.

Example:

```
GET    /movies
GET    /movies/{id}
POST   /movies
PUT    /movies/{id}
DELETE /movies/{id}
```

