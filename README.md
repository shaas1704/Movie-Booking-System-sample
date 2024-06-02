# Movie Booking Website

## Overview

Welcome to the Movie Booking Website project! This application allows users to browse movies, view showtimes, select seats, and book tickets for their favorite films. Built with a user-friendly interface and robust backend, this project aims to simplify the movie-going experience by providing a seamless and efficient ticket booking process.

## Features

- **Movie Listings**: Browse through a comprehensive list of current and upcoming movies.
- **Showtimes**: View available showtimes for each movie at different theaters.
- **Seat Selection**: Interactive seat selection for a more personalized booking experience.
- **User Authentication**: Secure user registration and login system.
- **Payment Integration**: Integrated payment gateway for hassle-free transactions.
- **Booking History**: Users can view their past bookings and manage upcoming ones.
- **Admin Panel**: Admin interface to manage movies, showtimes, and bookings.

## Technology Stack

- **Frontend**: HTML, CSS, JavaScript, React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Payment Gateway**: Stripe

## Getting Started

### Prerequisites

- Node.js
- MongoDB

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/movie-booking-website.git

2. Navigate to the project directory:
   ```bash
    cd movie-booking-website 

3. Install the frontend dependencies:
   ```bash
    cd client
    npm install

4. Install the backend dependencies:
   ```bash
    cd ../server
    npm install

### Configuration

1. Create a .env file in the server directory and add the following environment variables:
   ```bash
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    STRIPE_SECRET_KEY=your_stripe_secret_key

2. Start the backend server:
   ```bash
     npm run dev

3. Start the frontend development server:
    ```bash
     cd ../client
     npm start

## Usage
1. Register a new account or log in with existing credentials.
2. Browse movies and select a showtime.
3. Choose your preferred seats and proceed to payment.
4. Complete the payment to confirm your booking.
5. View your booking details in the 'My Bookings' section.

## Contributing
We welcome contributions to enhance the functionality and user experience of this project. Please fork the repository and submit pull requests for any improvements or bug fixes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
Thanks to the open-source community for providing valuable tools and libraries.
Special mention to the creators of the APIs and services used in this project.
