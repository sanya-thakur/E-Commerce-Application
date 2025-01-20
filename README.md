# E-Commerce-Application

# Ecommerce-Follow-Along Project

Ecommerce-Follow-Along is a comprehensive project designed to guide developers through the process of building an e-commerce application from scratch. This project will cover various aspects of web development, including front-end design, back-end integration, and database management, providing a hands-on learning experience.

## Milestone 1: Project Overview

In this session, we focused on the foundational elements of the Ecommerce-Follow-Along project. Key topics covered included:

### 1. Project Setup
- Initialized the GitHub repository.
- Set up the basic structure for the application.

### 2. Technology Stack
An overview of the technologies that will be utilized throughout the project:
- Node.js
- Express.js
- MongoDB
- React

### 3. Version Control
- Introduction to Git and GitHub for version control.
- Emphasis on best practices for committing code and managing branches.

### 4. Development Environment
- Configuration of local development environments to ensure consistency across team members.

This milestone sets the stage for further development and deeper exploration of e-commerce functionalities in upcoming sessions.

## Milestone 2: Project Setup and Login Page
In this milestone, we focused on setting up the initial front-end structure and implementing the login page for the application. Key achievements include:

### Front-End Framework:
- Set up the React framework with Vite for a fast and modern development experience.

### Folder Structure:
- Organized the `src` folder to include separate directories for `components`, `pages`, and `assets` to improve scalability and maintainability.

### Login Page Implementation:
- Developed a basic login page (`Login.jsx`) that includes a user interface for email and password input.
- Incorporated validation logic to ensure proper user input.

### Routing:
- Implemented React Router for navigation and created routes for the login and signup pages.

### Styling:
- Added basic styling using CSS (`App.css`) to ensure a clean and user-friendly design.

### Git Integration:
- Added the new files to version control and committed progress to the GitHub repository.

This milestone lays the groundwork for creating the front-end interface and interaction logic for the application.



## Milestone 3: Project Setup for Backend
In this milestone, the foundational backend structure for the e-commerce application was successfully established. Key achievements include:

### Backend Folder Structure:
- Organized the project into clearly defined folders (config, controller, db, middleware, model, and utility) to ensure scalability and maintainability.
### Database Integration:
- Set up a connection to MongoDB using Mongoose, enabling seamless interaction with the database.
### Environment Configuration
- Implemented a .env file to securely manage sensitive data such as database credentials, ensuring better security practices.
### Middleware Implementation
- Created essential middleware for authentication, error handling, and asynchronous error management to streamline request processing and ensure robust error handling.
### Utility Functions 
-Added reusable utility components like a custom error handler to improve consistency and simplify debugging.
### Git Integration
- Configured version control with Git and included a .gitignore file to exclude sensitive files and unnecessary folders like node_modules.

This milestone sets up a solid backend foundation for further development, including API implementation, user authentication, and business logic handling. It ensures that the project is structured, secure, and ready for future expansion.

## Milestone 4: Creating User Model and Controller

In this milestone, the focus was on implementing the user model and controller for managing user data and operations in the backend. Key achievements include:

### User Model:
- Created a `User` schema using Mongoose to define the structure for storing user information in the MongoDB database.
- Fields include essential user details such as name, email, password, and timestamps.
- Added validation for required fields and unique constraints for the email field.

### Password Hashing:
- Implemented password hashing using `bcrypt` to securely store user passwords in the database.

### User Controller:
- Developed a user controller to handle user-related backend operations such as registration and login.
- Added methods for creating new users and retrieving user details.

### API Endpoints:
- Set up API routes for user-related operations, including:
  - `/api/users/register`: Endpoint to register a new user.
  - `/api/users/login`: Endpoint to authenticate a user.

### Error Handling:
- Added error handling for scenarios such as duplicate email registration and invalid login credentials.

### Git Integration:
- Committed progress to version control, ensuring proper documentation of changes and updates.

This milestone provides the necessary backend infrastructure to manage user data, supporting future features like user authentication and authorization.


## Milestone 5: Creating the Signup Page
In this milestone, we focused on developing the signup page to enable users to create an account within the application. Key achievements include:

### Signup Page Implementation:
- Developed the `Signup.jsx` component with a user-friendly interface for account registration.
- Included form fields for user details such as name, email, and password.

### Form Validation:
- Added client-side validation logic to ensure proper input formatting and error messages for invalid entries.

### Integration with Routing:
- Configured navigation to and from the signup page using React Router for seamless user flow.

### Styling:
- Enhanced the design of the signup page to align with the application's overall styling for a consistent user experience.

### Code Organization:
- Refactored the code into reusable components where possible to promote cleaner and more maintainable code.

This milestone enhances the user experience by allowing new users to register, paving the way for further integration with back-end user authentication systems.

## Milestone 6: Encrypting Passwords and Storing User Data

In this milestone, the focus was on enhancing the security and data handling during the user registration process. Key achievements include:

### Password Encryption:
- Utilized `bcrypt` to hash user passwords during the signup process to ensure secure storage.
- Replaced plain-text password storage with hashed passwords in the database.

### Complete User Data Storage:
- Stored all user information, including name, email, and the hashed password, in the database using the `User` model.
- Ensured sensitive data is handled securely and adheres to best practices.

### Validation Enhancements:
- Added additional backend validation to verify that required fields are provided during signup.
- Prevented duplicate user registrations by ensuring email uniqueness in the database.

### API Integration:
- Updated the registration endpoint (`/api/users/register`) to handle password hashing and data storage seamlessly.

### Live Coding Walkthrough:
- Demonstrated the implementation of these features during a live coding session, explaining the importance of password encryption and secure data handling.

This milestone significantly enhances the application's security by protecting user credentials and laying a solid foundation for authentication and authorization in future milestones.

