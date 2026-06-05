
## Build a basic version of PayTM
# PayTM Clone

A full-stack digital payment application inspired by PayTM. Users can create accounts, log in securely, view balances, search users, and transfer money between accounts.

## Features

* User Registration and Login
* JWT Authentication
* Account Balance Management
* Money Transfer Between Users
* User Search Functionality
* Responsive User Interface
* RESTful API Integration

## Tech Stack

### Frontend

* React.js
* Vite
* React Router DOM
* Recoil
* Axios
* Tailwind CSS

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* Zod Validation

## Project Structure

├── frontend
│   ├── src
│   └── public
├── backend
│   ├── routes
│   ├── middleware
│   └── db.js
└── Dockerfile

## Installation

### Clone Repository

git clone <repository-url>

cd simple-paytm-main

### Backend Setup

cd backend

npm install

npm start

### Frontend Setup

cd frontend

npm install

npm run dev

## Environment Variables

Create a `.env` file in the backend directory:

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

## API Endpoints

### User

* POST /api/v1/user/signup
* POST /api/v1/user/signin
* PUT /api/v1/user

### Account

* GET /api/v1/account/balance
* POST /api/v1/account/transfer

## Screenshots

Add screenshots of:

* Sign Up Page
* Sign In Page
* Dashboard
* Transfer Money Page

## Future Enhancements

* Transaction History
* UPI Integration
* Email Notifications
* Profile Management
* Dark Mode

## Author

Gaurav Pardeshi

## License

This project is developed for learning and educational purposes.
