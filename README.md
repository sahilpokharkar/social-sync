# MERN Social Media App

A social media application built using the MERN stack (MongoDB, Express.js, React, Node.js).

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)

## Introduction

This MERN Social Media App allows users to create accounts, log in, and interact with posts and other users. Users can share posts, like, comment, and follow other users.

## Features

- User authentication and authorization
- Create, edit, and delete posts
- Like and comment on posts
- Follow and unfollow users
- Profile management
- File uploads (images, etc.)
- Responsive UI design

## Installation

To run this application locally, follow these steps:

### Prerequisites

Make sure you have the following installed:

- Node.js
- MongoDB

### Backend

1. Clone the repository:
    ```sh
    git clone https://github.com/sahilpokharkar/social-sync.git
    cd social-sync
    ```

2. Install dependencies:
    ```sh
    cd server
    npm install
    ```

3. Create a `.env` file in the `server` directory with the following environment variables:
    ```env
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret_key
    PORT=3001
    ```

4. Start the server:
    ```sh
    npm start
    ```

### Frontend

1. Install dependencies:
    ```sh
    cd ../client
    npm install
    ```

2. Start the development server:
    ```sh
    npm run dev
    ```

## Usage

1. Open your browser and navigate to `http://localhost:3000`.
2. Register a new account or log in with an existing account.
3. Create, edit, and interact with posts, follow other users, and manage your profile.

## Technologies Used

- **Frontend:**
  - React
  - Redux
  - @mui/material
  - Formik
  - Yup
  - React Router
  - Emotion (for styling)

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB
  - Mongoose
  - JWT (JSON Web Tokens)
  - bcrypt
  - Multer (for file uploads)
  - GridFS (for storing files)
  - dotenv (for environment variables)
  - Helmet (for security)
  - Morgan (for logging)

