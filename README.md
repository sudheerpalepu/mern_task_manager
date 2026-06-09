# mern_task_manager
# MERN Task Manager App

## Project Overview

This project is a MERN Stack Task Manager application developed as part of the B9IS130 module project setup exercise.

The application allows users to create, manage, update, and track tasks using:

* MongoDB Atlas (Database)
* Express.js (Backend Framework)
* React.js (Frontend Framework)
* Node.js (Runtime Environment)

---

## Project Structure

```text
mern_task_manager/
│
├── client/              # React Frontend
│
├── server/              # Express Backend
│   ├── models/
│   ├── routes/
│   ├── .env
│   └── server.js
│
├── README.md
└── .gitignore
```

---

## Technologies Used

### Frontend

* React.js
* JavaScript
* HTML5
* CSS3

### Backend

* Node.js
* Express.js
* Mongoose
* CORS
* Dotenv

### Database

* MongoDB Atlas

### Version Control

* Git
* GitHub

---

## Installation

### Clone Repository

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/mern-task-manager-app.git
cd mern-task-manager-app
```

---

## Backend Setup

Navigate to the server directory:

```bash
cd server
```

Install dependencies:

```bash
npm install
```

Create a `.env` file:

```env
MONGO_URI=your_mongodb_connection_string
PORT=3001
```

Run the backend:

```bash
node server.js
```

Expected output:

```text
MongoDB Connected
Server running on port 3001
```

---

## Frontend Setup

Navigate to the client directory:

```bash
cd client
```

Install dependencies:

```bash
npm install
```

Start React application:

```bash
npm start
```

The application will open in the browser at:

```text
http://localhost:3000
```

---

## API Endpoints

### Get All Tasks

```http
GET /api/tasks
```

### Create Task

```http
POST /api/tasks
```

Example Request Body:

```json
{
  "title": "Complete MERN Project Setup"
}
```

---

## Features

* Create tasks
* View all tasks
* MongoDB Atlas integration
* REST API using Express
* React frontend
* GitHub version control

---

## Development Progress

### Completed

* GitHub repository setup
* Express server setup
* MongoDB Atlas configuration
* Mongoose database connection
* Basic Task model creation
* REST API routes setup
* React frontend initialization

### Future Enhancements

* Update tasks
* Delete tasks
* User authentication
* Task categories
* Due dates
* Dashboard analytics

---

## Author

Sudheer Chowdary

B9IS130 Project

National College of Ireland

---

## License

This project is developed for educational purposes as part of the B9IS130 coursework.
