# audio

# AudioBook Application

This project is an AudioBook application with API endpoints for managing courses, audiobooks, and user registration/login.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [API Endpoints](#api-endpoints)
  - [Courses](#courses)
  - [Audiobooks](#audiobooks)
  - [User Registration/Login](#user-registrationlogin)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

- Node.js
- MongoDB (Make sure it's running)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/AudioBook-Application.git
Install dependencies:

bash
Copy code
cd AudioBook-Application
npm install
Configure environment variables:

Create a .env file in the project root and set the necessary variables:

env
Copy code
MONGODB_URI=your_mongodb_uri
PORT=your_preferred_port
Start the application:

bash
Copy code
npm start
The application should now be running on the specified port.

API Endpoints
Courses
GET /course/courses: Get all courses.
POST /course/add: Add a new course.
DELETE /course/delete/:id: Delete a course by ID.
Audiobooks
GET /audiobook/audioget: Get all audiobooks.
POST /audiobook/audioadd: Add a new audiobook.
GET /audiobook/audiogetBycId/:cid: Get audiobooks by course ID.
User Registration/Login
POST /register: Register a new user.
POST /login: User login.
