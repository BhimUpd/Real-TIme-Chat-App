# Realtime Chat App

A simple real-time chat application built with React and Spring Boot using WebSockets.

## Features

- Join chat rooms with a username
- Send and receive messages instantly
- Leave chat room functionality
- Press Enter to send messages

## Screenshots

**Joining Page**  
<img src="./public/login.png" alt="Login Screenshot" width="800"/>

**Chat Room (Multiple Users)**  
<div style="display: flex; gap: 10px;">
  <img src="./public/bhim.png" alt="Chat Screenshot 1" width="500"/>
  <img src="./public/bijay.png" alt="Chat Screenshot 2" width="500"/>
  <img src="./public/lochan.png" alt="Chat Screenshot 3" width="500"/>
</div>


## Tech Stack

- Frontend: React, Tailwind CSS
- Backend: Spring Boot, WebSocket (STOMP over SockJS)

## Getting Started

```bash
# Install frontend dependencies
npm install

# Start the frontend
npm run dev
