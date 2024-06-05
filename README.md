**Homely-Hub**
HomelyHub is an online hotel booking application built using the MERN stack (MongoDB, Express.js, React, Node.js). This application allows users to browse, book, and manage hotel reservations seamlessly.

**Table of Contents**
1.Introduction

2.Features

3.Technologies Used

4.Installation

5.Usage

6.API Endpoints

**Introduction**
HomelyHub provides an intuitive platform for users to book hotel rooms with ease. With a user-friendly interface and robust backend, it ensures a smooth booking experience. The application leverages the MERN stack to deliver a dynamic and responsive user experience.

**Features**

User Authentication: Secure login and registration using JWT.

-Hotel Search: Users can search for hotels based on location, price, and amenities. -Booking System: Book rooms with real-time availability updates. -User Dashboard: View and manage bookings. -Admin Panel: Admins can add, update, or remove hotels and manage bookings. -Responsive Design: Optimized for both desktop and mobile devices.

**Technologies Used**

Frontend:

React.js
Redux (for state management)
Axios (for API calls)
Bootstrap (for styling)
Backend:

Node.js
Express.js
MongoDB (with Mongoose for ORM)
Installation To get a local copy up and running, follow these simple steps:

i.Clone the repository:

(git clone https://github.com/yourusername/homelyhub.git cd homelyhub)

ii.Install dependencies for both frontend and backend:

Install backend dependencies
(cd backend npm install)

Install frontend dependencies
(cd ../frontend npm install)

iii. Set up environment variables:

Created a config.env file in the backend directory and add the following:

iv.Run the application:

Run backend
(cd backend npm start)

Run frontend
(cd ../frontend npm start)

The application will be accessible at http://localhost:3000 and the backend at http://localhost:5000.

**Usage**

1.Register a new user or log in with existing credentials.
2.Search for hotels by entering a location, check-in date, and check-out date.
3.View hotel details and available rooms.
4.Book a room and receive a confirmation.
5.Access the user dashboard to view and manage your bookings.

**API Endpoints**

User Authentication

POST /api/users/register: Register a new user
POST /api/users/login: Log in an existing user

Hotels

GET /api/hotels: Get a list of hotels
GET /api/hotels/:id: Get details of a specific hotel

Bookings

POST /api/bookings: Create a new booking
GET /api/bookings/user: Get bookings for a logged-in user

Admin

POST /api/admin/hotels: Add a new hotel
PUT /api/admin/hotels/:id: Update a hotel
DELETE /api/admin/hotels/:id: Delete a hotel
