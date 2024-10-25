# "Building a Chat App with Nodejs, Express and Socket.io"


## Overview
This is a real-time chat application where users can join different rooms and exchange messages instantly. Built with **[ Node.js, Express, Socket.io]**, the app allows users to join rooms, send messages, and see typing notifications.

![Chat App Screenshot](./path-to-screenshot)  
*Screenshot showing two users, Su and Josh, in the "food" chat room.*

---

## Features
- **User Authentication**: Users can choose a unique username and join chat rooms.
- **Real-Time Messaging**: Messages are instantly shared across users in the same chat room using WebSockets (Socket.io).
- **Typing Indicator**: Users can see when someone in the room is typing a message.
- **Room Management**: Users can join existing rooms or create new ones by entering a room name.
- **Active Room List**: Displays all active chat rooms and users within each room.

---

## Tech Stack
- **Frontend**: [JavaScript/ HTML / CSS]
- **Backend**: [Node.js / Express]
- **Real-Time Communication**: Socket.io

---

## Getting Started

### Prerequisites
Make sure the following software is installed on your local machine:
- **Node.js**: Download from [here](https://nodejs.org/).
- **[Your database, e.g., MongoDB]**: Make sure a database is up and running locally or in the cloud (e.g., MongoDB Atlas).

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/chat-app.git
   cd chat-app

2. **Install the necessary dependencies:**
   ```bash
   npm install

3. **Start the server:**
    ```bash
   cd server
   npm run dev

4. **Access the app:**
Open your browser and go to http://localhost:3500 to see the chat app in action.
