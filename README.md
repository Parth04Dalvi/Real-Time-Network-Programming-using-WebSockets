# Real-Time-Network-Programming-using-WebSockets 🗣️
This project showcases your ability to design and implement low-latency, bi-directional communication systems, which is critical for gaming, finance, and collaborative tools
Real-Time Multiplayer Chat Service (WebSockets) 

<img width="373" height="353" alt="image" src="https://github.com/user-attachments/assets/369edf50-f397-42da-ae24-da15cfd1cf55" />

Overview and Project Goal

This project implements a functional, low-latency Real-Time Multiplayer Chat System, showcasing proficiency in Network Programming, Full-Duplex Communication, and building modern, interactive frontends.

The system is split into two primary components: a sophisticated client interface (HTML/JavaScript with Socket.IO) and a lightweight server (Python/Flask-SocketIO). This architecture demonstrates the ability to design and orchestrate applications that require immediate, persistent data exchange, such as gaming, live collaboration, or financial tickers.

🚀 Architecture and Technology

The core of this system is the WebSocket protocol, which provides a single, long-lived, bi-directional connection between the client and server. This is essential for minimizing latency by eliminating the need for constant HTTP polling.
The project is built upon three core components:

Backend Service: Uses Python (Flask-SocketIO) to create the persistent WebSocket server and manages event-driven message routing (emit, broadcast).

Frontend Client: Built with HTML, JavaScript (Socket.IO), and Tailwind CSS. It manages the connection lifecycle, handles asynchronous message receiving, and provides a polished UI.

Network Protocol: WebSockets enables low-latency, full-duplex communication over a single TCP connection.

✨ Key Features

Real-Time Messaging: Instantaneous transmission and reception of messages achieved via the WebSocket protocol.

Interactive UI/UX: Utilizes a modal dialog for a focused connection experience and features dynamic styling, smooth transitions, and a dark theme.

User List and Status: Displays a real-time list of Active Users in a dedicated sidebar.

Typing Indicator: Implements the client-side logic for emitting typing signals and displays an animated, pulsing "..." indicator when other users are typing, significantly enhancing interactivity.

Connection Management: Handles the client-side connection lifecycle, including connect, disconnect, and error handling.

Execution

The project requires both the client (the HTML file) and the server (the Python file) to run simultaneously.

Server Setup:

Create a file named server.py and paste the Python code provided in the setup block (see the HTML file).

Install dependencies: pip install Flask Flask-SocketIO

Run the server: python server.py

Client Usage:

Open chat_client.html in your web browser.

The Connection Modal will appear. Enter a unique username and click Join Chat.

Open a second instance of chat_client.html (e.g., in a new tab) with a different username to test the real-time, bi-directional messaging and user list updates!
