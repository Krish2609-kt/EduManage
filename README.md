# School Management System - Backend API

![Node.js](https://img.shields.io/badge/Node.js-v18+-green)
![Express.js](https://img.shields.io/badge/Express.js-v4.18-blue)
![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-brightgreen)

This backend powers a comprehensive School Management System with role-based access control for administrators, teachers, and students.

## Features

- **Role-based authentication** for Admin, Teacher, and Student
- **Admin dashboard** for managing:
  - Employees
  - Students
  - Classes
  - Subjects
  - School information
  - Transport services
- **Teacher portal** for classroom management
- **Student portal** for academic activities
- **JWT authentication** with secure cookies
- **CORS support** for multiple frontend origins
- **Request logging** with Morgan

## Tech Stack

- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB (Mongoose ODM)
- **Middleware**:
  - `body-parser` - JSON request parsing
  - `cookie-parser` - Authentication cookies
  - `cors` - Cross-origin resource sharing
  - `morgan` - HTTP request logging

## API Structure
