# Chat Application

## Overview
This is a Java-based real-time chat application, designed to enable users to send and receive messages instantly. It supports both private and group chats with a simple and intuitive interface.

## Features
- Real-time messaging
- Private and group chat support
- User authentication
- Secure communication
- Easy-to-use GUI

## Technologies Used
- Programming Language: Java
- GUI Framework: Swing
- Networking: Sockets
- Build Tool: Apache Ant

## Installation

### Prerequisites
Ensure you have the following installed:
- Java Development Kit (JDK 8 or later)
- NetBeans IDE (Recommended)
- Git

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/chat-application.git
   cd chat-application
   ```
2. Open the project in NetBeans or another preferred IDE.
3. Build the project using Apache Ant:
   - Locate `build.xml` in the root directory.
   - Run the build command:
     ```sh
     ant build
     ```
4. Run the application:
   - Start the server:
     ```sh
     java -jar Server.jar
     ```
   - Start the client:
     ```sh
     java -jar Client.jar
     ```

## Usage
- Open the client application.
- Connect to the server using the provided IP address and port.
- Start chatting with other users!



