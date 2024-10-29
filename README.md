# geoAttend

geoAttend is a web-based attendance management system built using the MERN stack (MongoDB, Express, React, Node.js) and integrated with a face verification API. The application allows users to mark their attendance using facial recognition, ensuring accurate and efficient attendance tracking.

## Features

- **User Authentication**: Secure user registration and login functionality.
- **Facial Recognition**: Utilizes a face verification API for accurate attendance marking.
- **Attendance Tracking**: Users can view their attendance records over time.
- **Admin Dashboard**: Administrators can manage users and view attendance data.
- **Responsive Design**: The application is designed to be mobile-friendly.

## Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js with Express
- **Database**: MongoDB
- **Face Verification API**: (Specify the API you are using)

## Code Structure

The project is structured into separate folders for client and server:

- `client/`: Contains the React frontend application.
- `server/`: Contains the Node.js backend application.

### Key Components

- **Frontend Components**:
  - **Login**: User login page.
  - **Registration**: User registration page.
  - **Attendance**: Page to capture and verify attendance using facial recognition.
  - **Dashboard**: Admin dashboard for managing users and attendance records.

- **Backend Routes**:
  - **Auth Routes**: Handle user authentication (signup, login).
  - **Attendance Routes**: Manage attendance records and facial verification.

## Set Up

### Prerequisites

- Ensure you have Node.js and npm installed.
- MongoDB should be set up and running.

### Installation Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/geoAttend.git
   cd geoAttend
