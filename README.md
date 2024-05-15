# Task Manager Web Application

This is a Task Manager web application with separate frontend (client) and backend (server) directories.

## Prerequisites

- Node.js and npm installed
- MySQL server running locally or accessible

## Backend Setup (Server)

1. Navigate to the `server` directory:

   cd server
  

2. Install dependencies:

   npm install



3. Start the backend server:
   
   npm start


   The server will run on http://localhost:5000 by default.

## Frontend Setup (Client)

1. Navigate to the `client` directory:

   cd client


2. Install dependencies:

   npm install

3. Start the frontend development server:

   npm start


   The frontend development server will run on http://localhost:3000 by default.

## Usage

- Access the frontend application at http://localhost:3000 in your web browser.
- The backend API endpoints are available at http://localhost:5000/api.

## Project Structure

- `client`: Frontend React application.
- server`: Backend Node.js and Express application.
- index.js`: Entry point for the backend server.
  - routes/api.js`: API routes for task management.
