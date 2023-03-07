# Social Network API

This is an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list. It uses Node.js, NPM, and MongoDB for database management, and Insomnia to test the project.

## Installation

To use this app you will need to download and install the Terminal for Mac or GitBash for Windows. You may also need to install node.js, npm, MongoDB and insomnia to test the project. You will open the project in the code editor of your choice and then open the terminal and type <span style="color:orange">"npm install"</span> or "npm i" to install all the dependencies required. After installing MongoDB, on your terminal or GitBash you will need to type <span style="color:green">"mongod"</span> to start the server, this will allow a successfully connection with the project. Finally you will be able to start the project typing <span style="color:red">"npm start"</span> on your terminal or GitBash. And that is it, now you are able to test the code with insomnia!

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
