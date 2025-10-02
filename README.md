# Taskmaker
TaskMaster
A simple full-stack task management application built with React, Node.js, Express, and MongoDB.
Features

User authentication (signup/login) with JWT
Create, read, update, and delete tasks
Responsive UI with Tailwind CSS
RESTful API for task management
MongoDB for persistent storage

Project Structure

/client: React frontend
/server: Node.js/Express backend
/server/models: MongoDB schemas
/server/routes: API routes
/server/middleware: Authentication middleware

Setup Instructions

Clone the repository:git clone https://github.com/username/taskmaster.git
cd taskmaster


Backend Setup:
Navigate to /server
Install dependencies: npm install
Create a .env file with:MONGO_URI=mongodb://localhost:27017/taskmaster
JWT_SECRET=your_jwt_secret


Start the server: npm start


Frontend Setup:
Navigate to /client
Install dependencies: npm install
Start the React app: npm start


MongoDB:
Ensure MongoDB is running locally or provide a MongoDB Atlas URI in .env



Technologies

Frontend: React, Tailwind CSS, Axios
Backend: Node.js, Express, MongoDB, Mongoose, JWT
Tools: Git, npm

API Endpoints

POST /api/auth/signup: Register a new user
POST /api/auth/login: Login and receive JWT
GET /api/tasks: Get all tasks for the authenticated user
POST /api/tasks: Create a new task
PUT /api/tasks/:id: Update a task
DELETE /api/tasks/:id: Delete a task

# TaskMaster
A simple full-stack task management application built with React, Node.js, Express, and MongoDB.

## Features
- User authentication (signup/login) with JWT
- Create, read, update, and delete tasks
- Responsive UI with Tailwind CSS
- RESTful API for task management
- MongoDB for persistent storage
...
