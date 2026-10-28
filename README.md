# CN5006 – Tutorial 5: Express.js and MongoDB REST API

## Project Overview

This project was developed as part of the CN5006 Web and Mobile Development module at the University of East London.

The tutorial focuses on backend development using Node.js, Express.js, MongoDB and Mongoose to implement and test REST API endpoints.

## Technologies Used

- JavaScript (Node.js)
- Express.js
- MongoDB
- Mongoose
- HTML
- Visual Studio Code

## API Functionality

The application demonstrates database operations through the following REST API endpoints:

| HTTP Method | Endpoint | Description |
|---|---|---|
| POST | `/insertMany` | Inserts multiple person records into MongoDB. |
| GET | `/femalesOver30` | Retrieves female records aged 30 or above. |
| GET | `/countPersons` | Counts the total number of person records. |
| PATCH | `/updateManyPersons` | Updates the salary of female records to 5555. |
| DELETE | `/deleteManyPersons` | Deletes records where age is 45 or above. |

## Additional Features

The project also demonstrates basic Express routing, handling HTML form submissions, returning JSON responses and connecting an Express application to a MongoDB database.

## Running the Application

1. Install Node.js and MongoDB.
2. Clone the repository.
3. Open the project folder in a Terminal.
4. Install dependencies using `npm install`.
5. Ensure the local MongoDB service is running.
6. Start the application using `node index.js`.
7. Access the application at `http://127.0.0.1:3000`.

## Learning Outcomes

Through this tutorial, I developed practical experience in REST API implementation, asynchronous JavaScript programming, database CRUD operations, HTTP request handling and backend application debugging.

I also gained experience troubleshooting HTTP 404 errors, managing local development servers and using GitHub for version control.

## Academic Information

**Module:** CN5006 – Web and Mobile Development  
**Institution:** University of East London  
**Tutorial:** Week 5