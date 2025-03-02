# chatting-application

## Overview
This is a real-time chat application that allows users to send and receive messages instantly. It supports multiple users and provides a simple and intuitive interface for communication.

## Features
- Real-time messaging
- User authentication
- Private and group chats
- Typing indicators
- Online/offline status
- Message notifications
- Secure communication

## Technologies Used
- Frontend: HTML, CSS, JavaScript (React.js)
- Backend: Node.js, Express.js
- Database: MongoDB
- WebSocket: Socket.io
- Authentication: JWT (JSON Web Tokens)

## Installation

### Prerequisites
Ensure you have the following installed on your system:
- Node.js
- MongoDB
- Git

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/chat-app.git
   cd chat-app
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following:
     ```
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```
4. Start the backend server:
   ```sh
   npm start
   ```
5. Navigate to the frontend folder and install dependencies:
   ```sh
   cd frontend
   npm install
   ```
6. Start the frontend server:
   ```sh
   npm start
   ```

## Usage
- Open the application in your browser.
- Register or log in to start chatting.
- Create private or group chats.
- Enjoy real-time messaging with other users.

## Contributing
1. Fork the repository.
2. Create a feature branch:
   ```sh
   git checkout -b feature-branch-name
   ```
3. Commit changes:
   ```sh
   git commit -m "Add a new feature"
   ```
4. Push to your fork:
   ```sh
   git push origin feature-branch-name
   ```
5. Open a pull request.

