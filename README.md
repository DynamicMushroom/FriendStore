# FriendStore

Welcome to FriendStore! This project is dedicated to helping my friend build his dream business by creating an online store.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

FriendStore is an e-commerce platform designed to provide a simple and effective way for my friend to start and manage his own online store. This project aims to be user-friendly and customizable, offering a robust solution for small business owners.

## Features

- User Authentication
- Product Management
- Shopping Cart
- Order Processing
- Payment Integration (Stripe/PayPal)
- Responsive Design
- Admin Dashboard
- Inventory Management
- Customer Reviews
- Search and Filter Options

## Tech Stack

- **Frontend:** React, Bootstrap/Tailwind CSS
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **Payment Gateway:** Stripe/PayPal
- **Hosting:** Heroku/Netlify
- **Version Control:** Git

## Installation

To get a local copy up and running, follow these simple steps:

### Prerequisites

- Node.js and npm installed on your local machine

### Backend

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/FriendStore.git
    ```
2. Navigate to the backend directory:
    ```sh
    cd FriendStore/backend
    ```
3. Install NPM packages:
    ```sh
    npm install
    ```
4. Create a `.env` file and add your environment variables:
    ```env
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    STRIPE_SECRET_KEY=your_stripe_secret_key
    ```

5. Start the backend server:
    ```sh
    npm start
    ```

### Frontend

1. Navigate to the frontend directory:
    ```sh
    cd ../frontend
    ```
2. Install NPM packages:
    ```sh
    npm install
    ```
3. Start the frontend development server:
    ```sh
    npm start
    ```

## Usage

Once both the backend and frontend servers are running, you can access the application at `http://localhost:3000`. 

### Admin Access

To access the admin dashboard, you'll need to create an admin account or modify the user role directly in the database.

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Your Name - [@your-twitter-handle](https://twitter.com/your-twitter-handle) - your-email@example.com

Project Link: [https://github.com/your-username/FriendStore](https://github.com/your-username/FriendStore)
