# Encrypted-Real-Time-Chat

## Overview
This project implements a real-time chat application using the MERN stack (MongoDB, Express, React, Node.js). It ensures that urgent messages are processed first using a priority queue and provides secure communication by encrypting messages on the fly. User authentication is managed using hash tables.

## Features
- Real-time communication: Messages are sent and received in real-time using WebSocket.

- Message encryption: Messages are encrypted and decrypted on the fly to ensure secure communication.

- Priority queue: Ensures urgent messages are processed first.

- User authentication: Uses hash tables for quick lookup and verification.

## Technologies Used
- MongoDB: For storing user data and messages.

- Express.js: For creating the server and handling requests.

- React.js: For building the user interface.

- Node.js: For backend development and handling WebSocket connections.

- Socket.io: For real-time communication.

- Crypto: For encrypting and decrypting messages.

- Bcrypt: For hashing user passwords.

- JWT: For user authentication tokens.

- Cors: For enabling cross-origin requests.

## Installation 
1. Clone the repository:
```git clone <repository-url>```
2. Install dependencies for the server:
```cd server```
```npm install```
3. Install dependencies for the client:
```cd client```
```npm install```

## Usage
1. Start the server:
```cd server```
```npm start```
2. Start the client:
```cd client```
```npm start```
3. Open your browser and navigate to: http://localhost:3000

## Contributing
Feel free to contribute by opening issues or submitting pull requests. Please follow the contribution guidelines.

## License
This project is licensed under the MIT License.
