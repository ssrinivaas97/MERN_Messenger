
## MERN Chat Application
Welcome to the MERN Chat App, a real-time messaging platform built with the latest web technologies. This application utilizes MongoDB, Express.js, React.js, Node.js (MERN), and WebSocket for real-time bi-directional event-based communication.



## Prerequisites
Before you begin, ensure you have the following installed on your system:

Node.js and npm (Node Package Manager)
MongoDB running on the default port (27017)

## Installation
Clone the repository

git clone https://github.com/yourusername/mern-chat-app-yt.git
cd mern-chat-app-yt

Install backend dependencies
Navigate to the root directory of the project and install the required backend dependencies:


npm install


## Set up environment variables
Create a .env file in the root directory and add the necessary environment variables:

env
Copy code
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret

## Install frontend dependencies
Navigate to the frontend directory and install the required frontend dependencies:

cd frontend
npm install

## Build the React frontend for production use:


npm run build
Start the server

## Navigate back to the root directory and start the backend server:

npm run server
The application should now be running and accessible at http://localhost:5000.

Development
For development purposes, you can start the backend and frontend separately to take advantage of hot-reloading.

## To run the backend server:

npm run server
To run the frontend development server:
In a new terminal window, navigate to the frontend directory:

cd frontend
npm start
The React development server will start and open the application in your default web browser.

Testing
To test the application, simply register a new user account and log in. Once logged in, you can explore the real-time chat functionalities.

## Contributing
We welcome contributions to this project! Please consider the following guidelines before submitting your pull request:


