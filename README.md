# Task Management API

## Project Description
A simple RESTful API for managing tasks, built with Node.js, Express, and MongoDB.

## Setup Instructions
1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Create a `.env` file with the following contents:

MONGO_URI=your-mongodb-uri PORT=3000

4. Use `nodemon` to run the app:

npx nodemon app.js

5. Alternatively, you can also use `node app.js` to start the server.

## API Endpoints
- `GET /tasks`: Fetch all tasks.
- `GET /tasks/:id`: Fetch a task by ID.
- `POST /tasks`: Create a new task.
- `PUT /tasks/:id`: Update a task by ID.
- `DELETE /tasks/:id`: Delete a task by ID.
