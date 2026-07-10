# K-Chat
A real-time messaging app where users chat instantly in a shared room, built with WebSockets.

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

<p align="center">
<img src="https://github.com/user-attachments/assets/75cd5fb5-652a-4442-b644-3dbde629b7e1" alt="K-Chat in action" width="100%" />
</p>

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
