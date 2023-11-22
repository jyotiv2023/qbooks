# Full Stack E-Commerce Application

## Overview

This is a Full Stack E-Commerce Application designed and developed for purchasing books. It features separate user-facing and admin modules, user authentication, role-based authorization using JSON web tokens, and various functionalities like placing orders, payments using PayPal, adding product reviews, paginations, etc.

## Table of Contents

- [Features](#features)
- [Modules](#modules)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication and role-based authorization.
- User module for placing orders, adding product reviews, etc.
- Admin module for managing products, orders, and user roles.
- PayPal integration for secure payments.
- Pagination for better user experience.

## Modules

### User-Facing Module

This module is designed for end-users who want to browse and purchase books. It includes features such as:

- User registration and login.
- Browse and search for books.
- Add books to the cart and place orders.
- Leave product reviews.

### Admin Module

The admin module is designed for administrators to manage the application efficiently. Key features include:

- Manage products, categories, and inventory.
- View and manage user orders and reviews.
- Assign roles to users.

## Technologies Used

- Frontend:
  - React for building the user interface.
  - Redux for state management.
  - Bootstrap for responsive design.

- Backend:
  - Node.js and Express for server-side development.
  - MongoDB as the database using Mongoose.
  - JSON Web Tokens (JWT) for authentication.
  - PayPal API for payment processing.

## Getting Started

To get started with the project, follow these steps:

### Installation

1. Clone the repository: `git clone https://github.com/your-username/your-repo.git`
2. Navigate to the project directory: `cd your-repo`

### Configuration

1. Set up the backend:
   - Navigate to the `backend` folder: `cd backend`
   - Install dependencies: `npm install`
   - Configure environment variables (e.g., MongoDB connection string, JWT secret).

2. Set up the frontend:
   - Navigate to the `frontend` folder: `cd frontend`
   - Install dependencies: `npm install`
   - Configure environment variables (e.g., API endpoint).

### Usage

1. Start the backend server: `cd backend && npm start`
2. Start the frontend application: `cd frontend && npm start`

## Contributing

If you would like to contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`
3. Make your changes and commit them: `git commit -m 'Add feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
