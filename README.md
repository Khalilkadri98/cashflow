# Cashflow Project

This is a full-stack cashflow management application built with Vite, TypeScript, React, shadcn-ui, and Tailwind CSS on the frontend, and Express.js, TypeScript, and MongoDB on the backend.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
  - [Backend](#backend)
  - [Frontend](#frontend)
- [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [API Endpoints](#api-endpoints)
- [Learn More](#learn-more)
- [License](#license)

## Features

- Add, update, delete, and view cashflow entries.
- Responsive design using Tailwind CSS.
- State management with React and TypeScript.

## Prerequisites

Make sure you have the following installed on your machine:

- Node.js (>= 14.x)
- npm (>= 6.x)
- MongoDB (>= 4.x)

## Installation

### Backend

1. Clone the repository:

   ```bash
   git clone https://github.com/Khalilkadri98/cashflow
   cd cashflow/server
   ```
2. Install backend dependencies:

   ```bash
   npm install
   ```
3. Create a .env file in the server directory and add your MongoDB URI:

   ```bash
   PORT=5000
   MONGO_URI=your_mongodb_uri
   ```
4. Run the MongoDB server:

Ensure that your MongoDB server is running. If it's installed locally, you can start it with:

   ```bash
   mongod
   ```

### Frontend

1. Navigate to the client directory:

   ```bash
   cd ../client
   ```
2. Install frontend dependencies:

   ```bash
   npm install
   ```
## Running the Application

### Backend

To start the backend server, run:

   ```bash
   npm run dev
   ```
The backend server will start on http://localhost:5000.

### Frontend

To start the frontend development server, run:

   ```bash
   npm run dev
   ```
The frontend development server will start on http://localhost:3000.

## Project Structure

```plaintext
cashflow/
├── client/            # Frontend code (Vite, React, TypeScript, shadcn-ui, Tailwind CSS)
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── styles/
│   │   ├── App.tsx
│   │   ├── index.tsx
│   │   └── vite-env.d.ts
│   ├── public/
│   ├── index.html
│   └── vite.config.ts
├── server/            # Backend code (Express.js, TypeScript, MongoDB)
│   ├── src/
│   │   ├── controllers/
│   │   │   └── cashflowController.ts
│   │   ├── models/
│   │   │   └── Cashflow.ts
│   │   ├── routes/
│   │   │   └── cashflowRoutes.ts
│   │   └── index.ts
│   ├── .env
│   ├── package.json
│   ├── tsconfig.json
│   └── nodemon.json
└── README.md
```
## API Endpoints

### Cashflow Routes

- POST /api/cashflows - Create a new cashflow entry
- GET /api/cashflows - Get all cashflow entries
- PUT /api/cashflows/:id - Update a cashflow entry by ID
- DELETE /api/cashflows/:id - Delete a cashflow entry by ID

## Learn More

To learn more about the technologies used in this project, take a look at the following resources:

- [Vite Documentation](https://vitejs.dev/guide/) - Learn how to build fast web applications using Vite.
- [React Documentation](https://reactjs.org/docs/getting-started.html) - Explore the official React documentation to dive deeper into React concepts.
- [TypeScript Documentation](https://www.typescriptlang.org/docs/) - Learn how to use TypeScript, a typed superset of JavaScript that compiles to plain JavaScript.
- [shadcn-ui Documentation](https://shadcn-ui.dev/docs) - Learn more about the ShadCN UI library for building modern user interfaces.
- [Tailwind CSS Documentation](https://tailwindcss.com/docs) - Discover how Tailwind CSS helps you create custom designs using utility-first CSS.
- [Express.js Documentation](https://expressjs.com/) - Learn about Express.js, the web framework for Node.js used in building backend APIs.
- [MongoDB Documentation](https://docs.mongodb.com/) - Explore MongoDB, a NoSQL database used for storing application data.

## LICENSE
This project is licensed under the MIT License. See the LICENSE file for details.




