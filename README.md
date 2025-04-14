# 📨 Distributed Messaging System via TCP/IP (Java)

## 📘 Description

This project is a **console-based messaging application** developed in **Java**, which allows multiple clients to communicate with each other through a central server using the **TCP/IP protocol**. The system demonstrates basic principles of distributed systems and socket programming.

This project was developed as part of the **Distributed Systems course**.

---

## 👥 Team Members

- 🧑‍💻 **Đào Phan Quốc Hoài** – *Team Leader*
- 👨‍💻 **Lê Đức Thái**
- 👩‍💻 **Nguyễn Thị Vân Khánh**

---

## ⚙️ Technologies Used

- Java SE (Socket Programming)
- TCP/IP Protocol
- Java I/O Streams
- Multithreading

---

## 🎯 Objectives

- Build a simple distributed messaging system using low-level TCP sockets
- Understand and apply networking concepts like client-server model and multithreaded communication
- Strengthen Java programming and teamwork skills

---

## 🏗️ Architecture Overview

       +-------------+           +----------------+          +-------------+
       |  Client A   | <--->     |    Server      |  <-->    |  Client B   |
       +-------------+           +----------------+          +-------------+
                                          |
                                          |
                                     +-----------+
                                     | Client C  |
                                     +-----------+

- The **Server** listens for client connections and manages broadcasting messages.
- Each **Client** connects via TCP socket and communicates through the server.

---

## ✅ Features

- Multi-client support using threads
- Real-time text-based messaging
- Broadcast messages to all connected clients
- Graceful handling of client disconnections

---

## 🚀 Getting Started

### 1. Clone the repository:
```bash
git clone https://github.com/daophanquochoai/HeThongPhanTan.git
cd HeThongPhanTan
Đào Phan Quốc Hoài
📞 0779127667
📧 dpquochoai@gmail.com
🔗 LinkedIn Profile
