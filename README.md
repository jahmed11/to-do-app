# Todo Application

This project is a combined frontend and backend Todo application built with React, Vite, and Express. It allows users to manage their to-do items with functionalities to add, update, delete, and mark todos as completed.

## Project Structure

- **Frontend**: Built with React and Vite.
- **Backend**: Built with Express and serves the API for CRUD operations on todos.

## Git Repository

[GitHub Repository](https://github.com/jahmed11/to-do-app.git)

## Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v18 or later)
- [npm](https://www.npmjs.com/) (comes with Node.js)


## Setup


```bash
git clone https://github.com/jahmed11/to-do-app.git

cd to-do-app

Navigate to the Frontend Directory

cd frontend

Install Dependencies

npm install
# or
yarn install

# Create a `.env` file with:
# VITE_API_BASE_URL=http://localhost:3000/api

# for dev mode
npm run dev
# or
yarn dev

# For production build:
npm run build
# or
yarn build

# Navigate to the backend directory
cd backend

# Install Dependencies
npm install

# for dev mode
npm run dev

# server runs on localhost:3000


## note
## to run both the react app and express server on the same machine
## Build the frontend app using npm run build and then use dev mode
## for the backend to serve it as a static route
