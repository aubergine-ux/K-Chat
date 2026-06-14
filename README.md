# K-Chat
K-Chat is a real-time messaging application featuring user authentication and instant, synchronized messaging. 

---

## Overview

K-Chat lets users send and receive messages instantly in a shared web chat room. It uses WebSockets via Socket.io, establishing a live connection between the client and server.

---

## Features

- Real-time Messaging with WebSockets
- Instant Broadcasting to all Cnnected Users
- Lightweight Server Powered by Express.js
- Browser-based Client
- Live Connection/Disconnection Status
- Live Typing Status

---
### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/aubergine-ux/K-Chat.git
   cd K-Chat
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the server**
   ```bash
   node app.js
   ```

4. **Open in your browser**
   ```
   http://localhost:4000
   ```

Open a second browser tab or window to the same address and start chatting!

---

## Tutorial Series

This project was built by following the **Chat App using WebSockets (Node.js, Express & Socket.io)** series:

- [Part 1 — Setup & WebSocket basics](https://youtu.be/RUL9yTzOTuU?si=Afd4aLK7ebCOUIiN)

---

## License

This project is licensed under the [GNU General Public License v3.0](LICENSE).
