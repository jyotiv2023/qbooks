# Full Stack E-Commerce Application

## Overview

This is a Full Stack E-Commerce Application designed and developed for purchasing books. It features separate user-facing and admin modules, user authentication, role-based authorization using JSON web tokens, and various functionalities like placing orders, payments using PayPal, adding product reviews, paginations, etc.

## Table of Contents

- [Features](#features)
- [Modules](#modules)
- [Technologies Used](#technologies-used)


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
