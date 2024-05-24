Overview

Welcome to the Online Food Delivery Website project! This project is a full-featured web application developed using React, designed to provide users with a seamless experience for browsing, ordering, and paying for their favorite meals from various restaurants.

Features

User Authentication: Secure login and registration for users.
Restaurant Listings: Browse a variety of restaurants with detailed information and menus.
Search and Filter: Search for restaurants and filter by cuisine, ratings, and more.
Cart and Checkout: Add items to the cart and proceed with a secure checkout process.
Order History: View past orders and track current orders.
Responsive Design: Optimized for both desktop and mobile devices.
Technologies Used

Frontend:
React
React Router
Redux (for state management)
Axios (for API calls)
Material-UI (for UI components)

Backend:
Node.js
Express.js
MongoDB (Database)
JWT (for authentication)
Payment Gateway:
Stripe API
Getting Started

Prerequisites
Before you begin, ensure you have the following installed:

Node.js (v14.x or higher)
npm (v6.x or higher)
MongoDB (local or cloud instance)
Installation

Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/online-food-delivery.git
cd online-food-delivery

Install frontend dependencies:
bash
Copy code
cd client
npm install

Install backend dependencies:
bash
Copy code
cd ../server
npm install
Configuration

Backend:
Create a .env file in the server directory and add the following environment variables:

env
Copy code
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key

Frontend:
Create a .env file in the client directory and add the following environment variable:

env
Copy code
REACT_APP_API_URL=http://localhost:5000
REACT_APP_STRIPE_PUBLIC_KEY=your_stripe_public_key
Running the Application

Start the backend server:
bash
Copy code
cd server
npm start
The backend server should now be running on http://localhost:5000.

Start the frontend development server:
bash
Copy code
cd client
npm start
The frontend development server should now be running on http://localhost:3000.

Running Tests

To run tests for the frontend, navigate to the client directory and run:
bash
Copy code
npm test

To run tests for the backend, navigate to the server directory and run:
bash
Copy code
npm test
Contributing

We welcome contributions to enhance the features and improve the stability of the application. To contribute:

Fork the repository.
Create a new branch (git checkout -b feature/new-feature).
Make your changes and commit them (git commit -m 'Add new feature').
Push to the branch (git push origin feature/new-feature).
Open a pull request.
License

This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgements

Feel free to reach out if you have any questions or need further assistance! Happy coding! 🍕🍔🍣

Maintainer: Mit Kansagara
Contact: kansagramit2@gmail.com




