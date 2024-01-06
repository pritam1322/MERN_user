# MERN User Authentication Project

## Overview
This project is a full-stack web application developed using the MERN stack (MongoDB, Express.js, React.js, and Node.js) to manage user authentication. It offers functionalities for user registration, login, and secure authentication.

## Features
- **User Registration:** Allows new users to sign up with their email and password. Passwords are securely hashed before being stored.
- **User Login:** Existing users can log in using their registered email and password.
- **JWT Authentication:** Utilizes JSON Web Tokens (JWT) for secure authentication and session management.
- **Protected Routes:** Certain routes are protected and require authentication to access.
- **Error Handling:** Comprehensive error handling for various scenarios, including invalid inputs and duplicate emails.
- **Responsive UI:** Features a responsive user interface built using React.js, ensuring compatibility across different devices.

## Technologies Used
- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JSON Web Tokens (JWT)
- **Libraries:** bcrypt, axios, redux, vite and more.

## Setup and Installation
1. Clone the repository.
2. Navigate to the project directory and install dependencies using `npm install`.
3. Set up a MongoDB database and configure the connection in the backend.
4. Run the frontend and backend servers using `npm start` for both.

## Future Enhancements
- Implement OAuth for social media authentication.
- Enhance user profile management features.
- Improve security measures and error handling.
