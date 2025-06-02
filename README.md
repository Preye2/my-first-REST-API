# Express REST API #Node.js #Jest

A comprehensive RESTful API implementation with Express.js featuring CRUD operations, Joi validation, error handling, and automated testing.    

# Table of Contents

| Section | Description |
|---------|-------------|
| [Features](#features) | Key functionality of the API |
| [Installation](#installation) | Setup and configuration instructions |
| [API Documentation](#api-documentation) | Endpoint specifications |
| [Request Examples](#request-examples) | API usage samples |
| [Testing](#testing) | Test execution and coverage |
| [Project Structure](#project-structure) | Directory organization |
| [Troubleshooting](#troubleshooting) | Common issues and solutions |
| [Contributing](#contributing) | Development guidelines |



# Features

| Feature | Description |
|---------|-------------|
| **CRUD Operations** | Full Create, Read, Update, Delete functionality |
| **Validation** | Joi schema validation for requests |
| **Error Handling** | Custom error middleware with HTTP codes |
| **Logging** | Request/error logging |
| **Testing** | Jest test coverage for all endpoints |
| **Modular Architecture** | MVC pattern implementation |
| **CORS Support** | Cross-origin requests enabled |


# Installation Prerequisites
- Node.js v18+
- npm v9+ 

<center>**Installation**</center>center>

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   
# 1. Clone repository
git clone https://github.com/preye2/my-first-REST-API.git
cd express-rest-api

# 2. Install dependencies
npm install

# 3. Create environment file
cp .env.example .env

# 4. Start development server
npm run dev

# 5. Verify server status
curl http://localhost:3000
# Expected: "Hello, World!"

# Development Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start dev server (auto-restart) |
| `npm test` | Run all tests |
| `npm test -- --coverage` | Tests with coverage report |
| `npm run lint` | Lint code |
| `npm run format` | Format code |

# Configuration
- Development Scripts
# Environment Variables (.env)
PORT=3000
NODE_ENV=development
LOG_LEVEL=info

# Dependencies

"dependencies": {
  "cors": "^2.8.5",
  "dotenv": "^16.3.1",
  "express": "^4.18.2",
  "joi": "^17.13.0"
},
"devDependencies": {
  "jest": "^29.7.0",
  "nodemon": "^3.0.2",
  "supertest": "^6.3.3"
}

# API Documentation
# Base URL
- http://localhost:3000

# Endpoints

  Method	Endpoint	Description	Auth Required
GET	/	API status check	No
GET	/items	Get all items	No
GET	/items/:id	Get single item by ID	No
POST	/items	Create new item	No
PUT	/items/:id	Update item by ID	No
DELETE	/items/:id	Delete item by ID	No


[post implemetation](https://github.com/Preye2/my-first-REST-API/blob/main/Rest%20POST%20Implementation.jpg)
