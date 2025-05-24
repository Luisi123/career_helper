# Authentication App with Black and White Theme

A simple authentication application with a clean black and white theme, featuring login, registration, and protected routes.

## Features

- User registration and login
- JWT-based authentication
- Protected routes
- Clean black and white theme
- Responsive design
- MongoDB database integration

## Prerequisites

- Node.js (v14 or higher)
- MongoDB (running locally or a MongoDB Atlas account)
- npm or yarn

## Setup

1. Clone the repository
2. Install backend dependencies:
   ```bash
   npm install
   ```

3. Install frontend dependencies:
   ```bash
   cd client
   npm install
   ```

4. Create a `.env` file in the root directory with the following variables:
   ```
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/auth-app
   JWT_SECRET=your-super-secret-key-change-this-in-production
   ```

## Running the Application

1. Start the backend server:
   ```bash
   npm run dev
   ```

2. In a new terminal, start the frontend:
   ```bash
   cd client
   npm start
   ```

3. Open your browser and navigate to `http://localhost:3000`

## Project Structure

- `/client` - React frontend application
- `/server.js` - Express backend server
- `/package.json` - Backend dependencies
- `/client/package.json` - Frontend dependencies

## Security Features

- Password hashing using bcrypt
- JWT token-based authentication
- Protected routes
- Secure password storage
- Environment variable configuration

## Technologies Used

- Frontend:
  - React
  - Material-UI
  - React Router
  - Axios

- Backend:
  - Node.js
  - Express
  - MongoDB
  - Mongoose
  - JWT
  - bcryptjs