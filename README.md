# Ecommerce-Follow-Along Project Overview

## Project Description
Ecommerce-Follow-Along is a comprehensive project designed to guide developers through the process of building an e-commerce application from scratch. This project will cover various aspects of web development, including front-end design, back-end integration, and database management, providing a hands-on learning experience.

## Milestone 1: Project Overview

In this session, we focused on the foundational elements of the Ecommerce-Follow-Along project. Key topics covered included:

### 1. *Project Setup*
   - We initialized the GitHub repository and set up the basic structure for our application.

### 2. *Technology Stack*
   - An overview of the technologies that will be utilized throughout the project:
     - *Node.js*: JavaScript runtime for the back-end.
     - *Express.js*: Web framework for building the back-end API.
     - *MongoDB*: NoSQL database to store application data.
     - *React (MUI)*: Front-end framework using React with Material-UI for UI components.

### 3. *Version Control*
   - Introduction to *Git* and *GitHub* for version control.
   - Emphasized best practices for committing code and managing branches.

### 4. *Development Environment*
   - Configuration of local development environments to ensure consistency across team members.


---

   
## Milestone 2: Project Setup and Login Page
In this milestone, we focused on setting up the initial front-end structure and implementing the login page for the application. Key achievements include:
  
### Front-End Framework:
Set up the React framework with Vite for a fast and modern development experience.
### Folder Structure:
Organized the src folder to include separate directories for components, pages, and assets to improve scalability and maintainability.
### Login Page Implementation:
Developed a basic login page (Login.jsx) that includes a user interface for email and password input.
Incorporated validation logic to ensure proper user input.
### Routing:
Implemented React Router for navigation and created routes for the login and signup pages.
### Styling:
Added basic styling using CSS (App.css) to ensure a clean and user-friendly design.
### Git Integration:
Added the new files to version control and committed progress to the GitHub repository.
This milestone lays the groundwork for creating the front-end interface and interaction logic for the application.


---


## Milestone 3: Project Setup for Backend

In this milestone, the foundational backend structure for the e-commerce application was successfully established. Key achievements include:

### Backend Folder Structure:
Organized the project into clearly defined folders (config, controller, db, middleware, model, and utility) to ensure scalability and maintainability.

### Database Integration:
Set up a connection to MongoDB using Mongoose, enabling seamless interaction with the database.
Environment Configuration
Implemented a .env file to securely manage sensitive data such as database credentials, ensuring better security practices.
Middleware Implementation
Created essential middleware for authentication, error handling, and asynchronous error management to streamline request processing and ensure robust error handling.
Utility Functions
-Added reusable utility components like a custom error handler to improve consistency and simplify debugging.

### Git Integration
Configured version control with Git and included a .gitignore file to exclude sensitive files and unnecessary folders like node_modules.


---

## Milestone 4: Creating User Model and Controller
In this milestone, the focus was on implementing the user model and controller for managing user data and operations in the backend. Key achievements include:

### User Model:
Created a User schema using Mongoose to define the structure for storing user information in the MongoDB database.
Fields include essential user details such as name, email, password, and timestamps.
Added validation for required fields and unique constraints for the email field.

### Password Hashing:
Implemented password hashing using bcrypt to securely store user passwords in the database.

### User Controller:
Developed a user controller to handle user-related backend operations such as registration and login.
Added methods for creating new users and retrieving user details.

### API Endpoints:
Set up API routes for user-related operations, including:
/api/users/register: Endpoint to register a new user.
/api/users/login: Endpoint to authenticate a user.

### Error Handling:
Added error handling for scenarios such as duplicate email registration and invalid login credentials.

### Git Integration:
Committed progress to version control, ensuring proper documentation of changes and updates.
This milestone provides the necessary backend infrastructure to manage user data, supporting future features like user authentication and authorization.


---


## Milestone 5: Creating the Signup Page
In this milestone, we focused on developing the signup page to enable users to create an account within the application. Key achievements include:

## Signup Page Implementation:
Developed the Signup.jsx component with a user-friendly interface for account registration.
Included form fields for user details such as name, email, and password.

## Form Validation:
Added client-side validation logic to ensure proper input formatting and error messages for invalid entries.

## Integration with Routing:
Configured navigation to and from the signup page using React Router for seamless user flow.

## Styling:
Enhanced the design of the signup page to align with the application's overall styling for a consistent user experience.

## Code Organization:
Refactored the code into reusable components where possible to promote cleaner and more maintainable code.
This milestone enhances the user experience by allowing new users to register, paving the way for further integration with back-end user authentication systems.


---

Sure! Here’s a more concise version of the milestone:

---

## Milestone 6: Backend Implementation for Signup and Password Encryption

In this milestone, we created a backend endpoint for user signup, ensuring secure storage of user data by encrypting passwords before saving them in the database.

### Key Achievements:

**Password Encryption:**
   - Used `bcrypt` to hash passwords before storing them, ensuring passwords are never stored in plain text.

**Backend API for Signup:**
   - Created an endpoint to handle user registration, receiving and storing user data (name, email, encrypted password).

**Storing User Data Securely:**
   - Saved user data in the database with encrypted passwords for privacy and security.

**Error Handling:**
   - Implemented error messages for invalid data, like duplicate emails or weak passwords, and provided success responses.

**Database Integration:**
   - Integrated the backend with the database, creating models to store user data securely.

**Security Best Practices:**
   - Followed best practices with password hashing (bcrypt) and added salt to further secure passwords.


---

## Milestone 7: Backend Implementation for User Login

In this milestone, we focused on implementing the login functionality on the backend, allowing users to authenticate securely.

### Key Achievements:
- **Login Endpoint**: Created an API endpoint to receive user credentials (email/username and password).
- **Password Validation**: Used bcrypt to compare the entered password with the hashed password stored in the database.
- **User Authentication**: Returned success or error responses based on credential validity.
- **Security Best Practices**: Ensured password hashing to protect user data from being compromised.
  
This milestone sets up the user login process, validating credentials and ensuring data security during authentication.

---

## Milestone 8: Front-End Product Cards & Homepage Layout

In this milestone, we focused on creating a dynamic front-end layout to display product cards on the homepage.

### Key Achievements:
- **Card Component**: Designed a reusable product card component that accepts product details as props (e.g., name, image, price).
- **Homepage Layout**: Set up a grid or flexbox layout to display the product cards dynamically, iterating through the product list.
- **Reusable Design**: Ensured consistency and a clean design across all product cards.

This milestone enhances the user interface by showcasing products in a structured and visually appealing way, improving the browsing experience.

---

## Milestone 9: Front-End Form for Product Input

In this milestone, we created a form to allow users to add new products to the system.

### Key Achievements:
- **Product Form**: Built a form that collects product details such as name, price, description, and multiple images.
- **Multi-Image Input**: Implemented functionality to upload multiple product images.
- **Future Enhancements**: Suggested the addition of admin access and user profiles for product management.

This milestone sets the stage for adding products to the database, which will later be displayed on the homepage.

---

## Milestone 10: Product Schema & API Endpoint

### Key Achievements:
- **Product Schema Creation**: Created Mongoose schema for product data (name, description, price, image URL).
- **POST Endpoint**: Developed POST /api/products endpoint to store product data in MongoDB.
- **Data Validation**: Added validation to ensure correct and complete product data.
- **Error Handling**: Implemented error handling for invalid or incomplete data submissions.

---

## Milestone 11: Display Products on Homepage

### Key Achievements:
- **GET Endpoint**: Created GET /api/products endpoint to fetch product data from MongoDB.
- **Frontend Integration**: Integrated product data with React frontend using hooks for dynamic display in product cards.
- **Loading State**: Added loading state to indicate when product data is being fetched.
- **Error Handling**: Implemented error handling for failed data retrieval or API errors.

---

## Milestone 12: Displaying User-Specific Products

In this milestone, we focused on creating an endpoint to fetch and display products specific to a user based on their email, and rendering that data dynamically on the frontend.

### Key Achievements:
- **Endpoint for Product Retrieval**: Created an API endpoint to fetch all products associated with a user's email from MongoDB.
- **Frontend Integration**: Wrote a function to send a request to the backend and receive the user-specific products data.
- **Dynamic Data Rendering**: Displayed the retrieved products dynamically on the frontend using the product card component.
- **Data Filtering**: Implemented filtering logic on the backend to ensure that only products tied to the authenticated user's email are sent to the client.

---

## Milestone 13: Editing User Products

In this milestone, we added functionality for users to edit their uploaded products. 

### Key Achievements:
- **Edit Button**: Added an edit button to product cards.
- **Autofill Form**: Pre-filled the form with existing product details for easy editing.
- **Backend Update**: Created an endpoint to update product details in MongoDB.

---

## Milestone 14: Deleting User Products

In this milestone, we added the functionality to delete products.

### Key Achievements:
- **Delete Button**: Added a delete button to the product card.
- **Backend Endpoint**: Created an endpoint to delete products from MongoDB using the product ID.
- **Frontend Integration**: Enabled the frontend to send the product ID to the backend for deletion when the delete button is clicked.

---

## Milestone 15: Creating and Integrating a Navbar

In this milestone, we focused on creating and integrating a reusable Navbar component to enhance the navigation experience in our application.

### Key Achievements:
- **Navbar Component**: Created a Navbar component with links to all pages, including Home, My Products, Add Product, and Cart.
- **Responsive Design**: Made the Navbar responsive, ensuring it looks good on all screen sizes.
- **Frontend Integration**: Integrated the Navbar component into all pages to enable smooth and easy navigation between different sections of the app.

---
