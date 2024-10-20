# Amazon Clone

A fully functional **Amazon Clone** built using **React**, **Firebase**, **HTML**, and **CSS**. This project replicates key features of Amazon's e-commerce platform, including product browsing, user authentication, a shopping cart, and a checkout process.

![Amazon Clone Screenshot](path/to/screenshot.png)

## Features

### 1. User Authentication
- **Sign Up / Login**: Users can create accounts or log in with their existing credentials.
- **Firebase Authentication**: Handles secure user authentication and session management.
- **Protected Routes**: Ensures only logged-in users can access certain pages (e.g., Checkout).

### 2. Product Listing & Search
- **Home Page**: Displays a range of products from different categories with detailed descriptions and pricing.
- **Product Search**: Users can search for products using a search bar, similar to Amazon’s search functionality.
- **Product Details**: Each product has its own detailed page with an image, title, price, and customer reviews.

### 3. Shopping Cart
- **Add to Cart**: Users can add multiple items to their cart.
- **Remove from Cart**: Items can be removed from the cart.
- **Cart Preview**: Shows the cart contents, total price, and number of items in real-time.

### 4. Checkout System
- **Order Summary**: Users can view their cart and proceed to checkout.
- **Delivery Address**: Users input their delivery information during checkout.
- **Payment Integration**: Simulated payment flow using [payment provider of your choice], with real-time updates in Firebase.

### 5. Firebase Integration
- **Realtime Database**: Stores user data, product listings, and orders.
- **Firestore**: Manages orders and cart details in real-time.
- **Firebase Hosting**: Deployed on Firebase for fast, scalable web hosting.
- **Authentication**: Secured user login system powered by Firebase Authentication.

## Tech Stack

- **React**: Frontend JavaScript library used to create the dynamic and responsive user interface.
- **Firebase**: For backend services like authentication, real-time database, Firestore, and hosting.
- **HTML & CSS**: Markup and styling to replicate the Amazon UI/UX.
- **React Context API**: To manage the global state of the application, including the cart and user session.

## Live Demo

Check out the live version of the Amazon Clone here: [Live Demo URL](https://mellifluous-kheer-214a62.netlify.app/)

## Installation

Follow these steps to set up the project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/amazon-clone.git
   npm install
   npm start


