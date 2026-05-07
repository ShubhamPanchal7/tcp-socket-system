# ⚡ TCP Socket Communication System

<div align="center">

<img src="https://img.shields.io/badge/Node.js-Backend-green?style=for-the-badge&logo=node.js" />
<img src="https://img.shields.io/badge/TCP-Socket%20Programming-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/JavaScript-ES6-yellow?style=for-the-badge&logo=javascript" />
<img src="https://img.shields.io/badge/Real--Time-Communication-orange?style=for-the-badge" />

<br><br>

A beginner-friendly TCP Client-Server communication project built using **Node.js**.
This project demonstrates how socket-based communication works using the TCP protocol for sending and receiving real-time messages between a client and a server.

</div>

---

# 🚀 Project Overview

This project was developed while learning **JavaScript** and **Node.js networking concepts**.
It showcases the implementation of a simple TCP socket system capable of:

* Establishing client-server connections
* Sending requests from client to server
* Handling server responses
* Demonstrating real-time communication flow

---

# 🌟 Features

<table>
<tr>
<td width="50%">

### 🖥️ Server Functionality

* TCP socket server creation
* Handles incoming client connections
* Processes client requests
* Sends responses back to clients

</td>

<td width="50%">

### 💻 Client Functionality

* Connects to TCP server
* Sends dynamic requests
* Receives server responses
* Handles connection termination

</td>
</tr>
</table>

---

# 🛠️ Technologies Used

<div align="center">

| Technology      | Purpose                  |
| --------------- | ------------------------ |
| 🟢 Node.js      | Runtime Environment      |
| 🌐 TCP Protocol | Socket Communication     |
| 🧠 JavaScript   | Application Logic        |
| ⚡ Net Module    | Networking Functionality |

</div>

---

# 📂 Project Structure

```bash id="gw7e2n"
TCP-Socket-System/
│
├── client.js
├── server.js
└── README.md
```

---

# 🔄 Communication Flow

```bash id="c1g4q2"
Client  --->  TCP Request  --->  Server
Server  --->  Response     --->  Client
```

---

# 💡 Example Requests

## 🎲 Mathematical Request

```js id="1gq9xt"
const mathReq = "math 9*6+45-0";
```

### ✅ Expected Output

```bash id="h3qk9m"
Response: 99
```

---

## 💻 Program Request

```js id="2u9lza"
const programReq = "console.log('hello')";
```

---

# 🚀 Getting Started

## 📥 Clone Repository

```bash id="r9g1pl"
git clone https://github.com/your-username/tcp-socket-system.git
```

---

## 📂 Navigate to Project Folder

```bash id="m3t8qa"
cd tcp-socket-system
```

---

## ▶️ Start Server

```bash id="h82kdp"
node server.js
```

---

## 💻 Run Client

```bash id="x4t8ja"
node client.js
```

---

# 📸 Sample Console Output

## 🖥️ Server Console

```bash id="qp0d5k"
Server running on port 5000
Client connected
Request received: math 9*6+45-0
```

---

## 💻 Client Console

```bash id="k0v7dw"
Connected to server
Response: 99
Disconnected from server
```

---

# 🎯 Learning Outcomes

Through this project, concepts learned include:

* TCP socket programming
* Client-server architecture
* Node.js networking
* Real-time communication
* Event-driven programming

---

# 🔮 Future Improvements

* Multi-client support
* Chat system implementation
* File transfer functionality
* Encrypted communication
* GUI frontend integration
* Command parser enhancement

---

# 👨‍💻 Developer

<div align="center">

## Shubham Panchal

💻 Passionate Web Developer
⚡ Exploring Backend Development & Networking

</div>

---

# ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!
