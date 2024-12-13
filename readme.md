# Employee Management System: Full-Stack Web Application with React, Tailwind CSS, and Spring Boot

This repository contains a full-stack web application that implements an employee management system. The project leverages modern technologies to demonstrate how a reactive frontend integrates seamlessly with a powerful backend.

## Features

### 1. **Complete Functionality:**
- Create, edit, delete, and list employees.
- User-friendly interface with smooth integration between frontend and backend.

### 2. **Technologies:**
- **Frontend:** React with Tailwind CSS for a responsive and modern design.
- **Backend:** Spring Boot for providing REST APIs.
- **Database:** MySQL as the relational database system.

## Backend Development (Spring Boot)

### a. Project Setup
- Creation of a Spring Boot application with the following dependencies:
  - Lombok
  - JPA
  - MySQL Driver
  - Spring Web

### b. Database Configuration
- MySQL database setup with configurations:
  - URL
  - Username
  - Password

### c. REST APIs
- Save, retrieve, update, and delete employees.
- Advanced CORS configuration for cross-origin requests.

## Frontend Development (React)

### a. Project Setup
- Creation of the React application using `npx create-react-app`.
- Integration of Tailwind CSS via npm and configuration in `tailwind.config.js`.

### b. Component-Based Architecture
- **Navbar Component:** Main navigation.
- **Add Employee:** Form to add new employees styled with Tailwind CSS.
- **Employee List:** Display all employees in a table.

### c. State Management and API Calls
- **State Management:** Using `useState` and `useEffect` hooks.
- **API Calls:** Axios for communication with the backend.
- Centralized service class to manage API interactions.

### d. Routing and Navigation
- Implementation of React Router to manage multiple pages:
  - Employee list
  - Add and edit employees

### e. Optimizations
- Reusable components for individual employees.
- Parent-child component communication for dynamic updates.

## Setup and Installation

### Prerequisites:
- Node.js and npm
- MySQL database
- Java 17 or higher

### Steps:
1. **Backend:**
   - Clone the repository and import it into IntelliJ IDEA or a similar IDE.
   - Configure database details in `application.properties`.
   - Run the application using `mvn spring-boot:run`.

2. **Frontend:**
   - Navigate to the `frontend` directory.
   - Install dependencies with `npm install`.
   - Start the React application with `npm start`.

