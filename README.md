# Ecommerce Platform

A full-stack ecommerce platform built with Node.js, Express, MongoDB, and React. This project provides a robust foundation for online shopping, including user authentication, product management, cart functionality, and order processing.

## Features

- User authentication (register, login, forgot password)
- Admin dashboard for managing products, categories, and users
- Product listing, search, and filtering
- Shopping cart and checkout
- Order management
- Responsive UI with React

## Project Structure

```
Ecommerce-Platform/
├── server.js                # Entry point for Express server
├── config/                  # Database configuration
├── controllers/             # Express route controllers
├── helpers/                 # Helper functions
├── middlewares/             # Express middlewares
├── models/                  # Mongoose models
├── routes/                  # Express routes
├── image/                   # Product images
├── client/                  # React frontend
│   ├── public/              # Static assets
│   └── src/                 # React source code
│       ├── components/      # Reusable components
│       ├── context/         # React context providers
│       ├── hooks/           # Custom hooks
│       ├── pages/           # Page components
│       └── styles/          # CSS styles
```

## Getting Started

### Prerequisites

- Node.js
- MongoDB
- pnpm (or npm/yarn)

### Backend Setup

1. Install dependencies:
   ```sh
   pnpm install
   ```
2. Configure MongoDB in `config/db.js`.
3. Start the server:
   ```sh
   node server.js
   ```

### Frontend Setup

1. Navigate to the `client` folder:
   ```sh
   cd client
   ```
2. Install dependencies:
   ```sh
   pnpm install
   ```
3. Start the React app:
   ```sh
   pnpm start
   ```

## Environment Variables

Create a `.env` file in the root and add your MongoDB URI and other secrets:

```
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```
