# Social Network API

This is an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list. It uses Node.js, NPM, and MongoDB for database management, and Insomnia to test the project.

## Installation

1. Clone the repository
2. Run `npm install` to install the required dependencies
3. Start the server with `npm start`

## Usage

### User Routes

- GET `/api/users`: Get all users
- GET `/api/users/:id`: Get user by ID
- POST `/api/users`: Create a new user
- PUT `/api/users/:id`: Update user by ID
- DELETE `/api/users/:id`: Delete user by ID

### Thought Routes

- GET `/api/thoughts`: Get all thoughts
- GET `/api/thoughts/:id`: Get thought by ID
- POST `/api/thoughts`: Create a new thought
- PUT `/api/thoughts/:id`: Update thought by ID
- DELETE `/api/thoughts/:id`: Delete thought by ID

### Friend Routes

- POST `/api/users/:userId/friends/:friendId`: Add a friend to a user's friend list
- DELETE `/api/users/:userId/friends/:friendId`: Remove a friend from a user's friend list

## Technologies Used

- Node.js 🟢
- NPM     📦
- MongoDB  🍃
- Insomnia  🛌

# Walkthrough Demo Video 🎥 
