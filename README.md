# NagaEd API

## Overview
This is a simple RESTful API for managing a list of educational courses. It allows users to perform basic CRUD (Create, Read, Update, Delete) operations.

## Technology Stack
- Node.js
- Express.js
- JSON for data storage

## Project Structure
nagaed-api/ │ ├── package.json ├── package-lock.json ├── server.js ├── routes/ │ └── courses.js ├── controllers/ │ └── courseController.js ├── models/ │ └── courseModel.js └── data/ └── courses.json

## API Endpoints

- `GET /api/courses`: Retrieve all courses
- `POST /api/courses`: Add a new course
- `PUT /api/courses/:id`: Update a course by ID
- `DELETE /api/courses/:id`: Delete a course by ID

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/nagaed-api.git
Navigate into the project directory:



cd nagaed-api
Install the dependencies:

bash

npm install
Start the server:



node server.js
The server will run at http://localhost:3000.
http://localhost:3000/api/courses



