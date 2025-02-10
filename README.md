# Wanderlust web-app

## Project Overview:
Wanderlust is a backend-focused web application inspired by Airbnb. It is designed to provide a seamless experience for users to browse, book, and manage travel accommodations. Built using Node.js, Express.js, MongoDB, and EJS, the project follows the MVC (Model-View-Controller) architecture to ensure clean code separation and maintainability.
## Tech Stack:
Backend: Node.js, Express.js
Database: MongoDB
Templating Engine: EJS (Embedded JavaScript)
Architecture: MVC (Model-View-Controller)
##Features:
User Authentication:
Sign-up/Login functionality with session-based authentication (Passport.js or JWT).
Role-based access (Admin, Host, Guest).
Property Listings (CRUD Operations):
Hosts can add, update, delete, and manage property listings.
Users can browse available stays.
Booking System:
Users can book available properties.
Hosts can manage bookings.
Reviews & Ratings:
Guests can leave reviews and ratings for properties.
Reviews are displayed dynamically using EJS.
##MVC Architecture Implementation:
Model (M - MongoDB & Mongoose):
Defines schemas for users, properties, bookings, and reviews.
Handles database operations.
View (V - EJS Templates):
Displays dynamic content (property listings, user details, reviews).
Uses Bootstrap for styling (optional).
Controller (C - Express.js Routes & Logic):
Manages API endpoints for authentication, bookings, and property listings.
Handles business logic and database interactions.

