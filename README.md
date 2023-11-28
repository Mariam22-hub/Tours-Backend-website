# Express.js Tour Booking Application

## Description

This application is a comprehensive Node.js project that incorporates user authentication, tour booking, review management, and more. It uses Express for routing, Mongoose for MongoDB database interactions, and integrates several middleware for enhanced functionality.

## Installation

Clone the repository and install the dependencies:

```
git clone [Your-Repository-URL]
cd [Your-Repository-Directory]
npm install
```
## Configuration
Create a .env file in the project root and update it with your MongoDB URI, Database Password, and other necessary environment variables.

Example .env file:
```
DATABASE=your_mongodb_uri
DATABASE_PASSWORD=your_database_password
PORT=3000
```

## Running the Application
Run the application with the following command:
```npm start```


## Features

### Authentication
- User authentication (signup, login, password reset).
- Role-based access control (admin, guide, user).

### Tours
- CRUD operations for tours.
- Advanced tour search and filtering.
- Tour statistics and monthly plans.

### Bookings
- Booking management for tours.
- Secure checkout process.

### Reviews
- Users can post and manage reviews for tours.

### User Profile
- Users can update their profiles and manage bookings.

## API Endpoints

The application exposes several RESTful API endpoints:

### Tours
- `GET /api/v1/tours`: Retrieve all tours.
- `POST /api/v1/tours`: Create a new tour.
- `GET /api/v1/tours/:id`: Retrieve a single tour.
- `PATCH /api/v1/tours/:id`: Update a tour.
- `DELETE /api/v1/tours/:id`: Delete a tour.

### Users
- `POST /api/v1/users/signup`: User signup.
- `POST /api/v1/users/login`: User login.
- `GET /api/v1/users/logout`: User logout.
- `PATCH /api/v1/users/updateMe`: Update user data.
- `DELETE /api/v1/users/deleteMe`: Delete user account.
- `GET /api/v1/users/:id`: Retrieve a single user.
- `PATCH /api/v1/users/:id`: Update a user.
- `DELETE /api/v1/users/:id`: Delete a user.

### Reviews
- `GET /api/v1/reviews`: Retrieve all reviews.
- `POST /api/v1/reviews`: Create a new review.
- `GET /api/v1/reviews/:id`: Retrieve a single review.
- `PATCH /api/v1/reviews/:id`: Update a review.
- `DELETE /api/v1/reviews/:id`: Delete a review.

### Bookings
- `GET /api/v1/bookings`: Retrieve all bookings.
- `POST /api/v1/bookings`: Create a new booking.
- `GET /api/v1/bookings/:id`: Retrieve a single booking.
- `PATCH /api/v1/bookings/:id`: Update a booking.
- `DELETE /api/v1/bookings/:id`: Delete a booking.

