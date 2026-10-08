# Everything Pokémon — Frontend

This is the frontend portion of my **Everything Pokémon** full-stack web application.

The application provides an interactive Pokémon experience where users can explore Pokémon information through a responsive React-based interface. The frontend communicates with a custom backend API to handle application data, authentication, and user-related functionality.

## Live Demo

[Everything Pokémon](https://pokemon-website-frontend.vercel.app/)

## Technologies Used

- React
- JavaScript
- HTML5
- CSS3
- Axios
- REST APIs
- Vercel

## Full-Stack Architecture

This project is built as a full-stack application consisting of:

- **Frontend:** React application responsible for the user interface and client-side functionality.
- **Backend:** Node.js and Express.js API responsible for server-side logic, authentication, and database communication.
- **Database:** MongoDB with Mongoose for storing application data.

### Backend Technologies

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Axios
- bcrypt
- CORS
- dotenv

## Features

- Interactive Pokémon-focused user interface
- Pokémon data displayed through API requests
- Frontend-to-backend API communication
- User authentication
- Responsive web interface
- Reusable React components
- Dynamic application data
- Secure authentication using JWT

## Getting Started

### 1. Clone the repository

```bash
git clone <your-frontend-repository-url>
cd <your-frontend-repository-name>
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm run dev
```

The application will run locally at:

```text
http://localhost:3000
```

## Environment Variables

Create a `.env` file in the root directory and add the required backend API URL.

Example:

```env
VITE_API_URL=<your-backend-api-url>
```

> The exact environment variable name should match the one used in the project.

## Deployment

The frontend is deployed using **Vercel**.

Live application:

https://pokemon-website-frontend.vercel.app/

## Project Purpose

This project was built as a full-stack software engineering project to practice developing a complete web application using React, Node.js, Express.js, MongoDB, authentication, REST APIs, and deployment.

The project demonstrates my ability to build and connect a frontend application with a custom backend API rather than relying solely on a frontend-only application.
