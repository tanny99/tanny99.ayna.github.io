Flutter Chat Application

This project is a multi-session, multi-user chat application built using Flutter. It allows users to establish and maintain multiple chat sessions simultaneously, communicating in real-time with a server using WebSockets.

Features

Multi-User Support: Supports multiple users, enabling individual and distinct chat sessions.
Real-Time Communication: Utilizes WebSockets to provide real-time communication. Every message sent from a client is echoed back by the server, simulating a chat environment.
Persistent Sessions: Integrates Hive for local data storage to maintain and restore chat sessions even after the app restarts or the device reboots.
User Authentication: Leverages Firebase Authentication to manage user authentication, ensuring secure access to the chat sessions.
Multiple Sessions: Users can start and manage multiple chat sessions simultaneously, each connected to the server independently.
Technologies Used

Flutter: Used for creating the user interface and managing the application state.
Hive: Implements local storage to persist chat sessions, enhancing the user experience by retaining session data across app launches.
WebSocket Echo Test Server: Employs a WebSocket echo server (wss://echo.websocket.events) for message sending and receiving, which echoes back the messages sent by users, mimicking a chat server.
Firebase: Utilizes Firebase for robust user authentication, ensuring that each user session is securely managed.
