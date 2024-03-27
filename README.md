# MERN Chat Application

This is a simple chat application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to join chat rooms and communicate in real-time.

## Features

- User authentication: Users can sign up, log in, and log out securely.
- Real-time messaging: Users can send and receive messages in real-time within chat rooms.
- Multiple chat rooms: Users can join different chat rooms and engage in separate conversations.
- Responsive design: The application is designed to work seamlessly across various devices and screen sizes.

## Technologies Used

- MongoDB: A NoSQL database used to store user information and chat messages.
- Express.js: A Node.js framework used to build the backend server and handle HTTP requests.
- React.js: A JavaScript library used for building the user interface.
- Node.js: A JavaScript runtime used for server-side logic and handling WebSocket connections.
- Socket.IO: A library used for real-time, bidirectional communication between clients and servers.

## Installation

1. Clone the repository:
    git clone https://github.com/yourusername/mern-chat-app.git

2. Navigate to the project directory:
    cd mern-chat-app

3. Install server dependencies:
   npm install

4. Navigate to the client directory:
    cd client

5. Install client dependencies:
    npm install

6. Return to the project root directory:
   cd ..

7. Start the server:
   npm start
   
9. Start the client:
    cd client
    npm start

9. Open your browser and visit `http://localhost:3000` to view the application.

## Configuration

- Create a `.env` file in the root directory of the project.
- Add the following environment variables:

MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key


Replace `your_mongodb_connection_string` with your MongoDB connection string and `your_jwt_secret_key` with a secret key for JWT token generation.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.




