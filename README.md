# Real-Time Chat Application

## Description

This is a real-time chat application built using **Node.js, Express.js, and Socket.IO**. The application allows multiple users to communicate instantly without refreshing the page. It uses WebSocket technology to enable fast, bidirectional communication between the client and server.

The project features a modern and aesthetic user interface with chat bubbles, timestamps, and a responsive design, providing a smooth and interactive user experience.

---

## Features

* Real-time messaging (no page refresh required)
* Username-based chat system
* Chat bubbles (sent and received messages)
* Timestamp for each message
* Aesthetic UI with dark theme and gradient background
* Responsive design (works on different screen sizes)
* Smooth scrolling chat window

---

## Technologies Used

### Frontend:

* HTML
* CSS
* JavaScript

### Backend:

* Node.js
* Express.js
* Socket.IO

### Tools:

* Visual Studio Code
* Git & GitHub

---

## Installation & Setup

Follow these steps to run the project locally:

### 1. Clone the repository

```bash
git clone https://github.com/sindhukarnala05-crypto/chat-app.git
cd chat-app
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run the server

```bash
node server.js
```

### 4. Open in browser

```
http://localhost:3000
```

### 5. Test the application

* Open multiple tabs in your browser
* Enter different usernames
* Start chatting in real-time

---

## Screenshots
![alt text](image-2.png)
![alt text](image-3.png)
---

## How It Works

1. User opens the application in a browser
2. A WebSocket connection is established with the server
3. User sends a message
4. The server receives the message using Socket.IO
5. The server broadcasts the message to all connected users
6. Messages appear instantly on all screens

---

## Project Structure

```
chat-app/
│── public/
│   └── index.html
│── server.js
│── package.json
│── README.md
```

---

## Future Enhancements

* User authentication (login/signup)
* Database integration (store chat history)
* Private messaging
* Emoji support
* File/image sharing
* Online/offline user status
* Notifications

---

## Limitations

* Messages are not stored (no database)
* No user authentication system
* No private chat functionality
* Basic security implementation

---

## Learning Outcomes

* Understanding of WebSockets and real-time communication
* Hands-on experience with Node.js and Socket.IO
* Building interactive and dynamic web applications
* Designing modern UI using HTML and CSS

---

## 👤 Author

K.Sindhu Sahithi

---

## Acknowledgement

This project was developed as part of learning Web Technologies and demonstrates real-time communication using modern web development tools.

---

## Note

Make sure Node.js is installed on your system before running this project.
