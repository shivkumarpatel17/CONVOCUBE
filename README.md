# ConvoCube - Chat Application

ConvoCube is a real-time chat application that provides messaging and group chat functionality. The app allows users to sign in, chat with others, create and manage groups, and more. It uses modern technologies like React, Redux, Socket.io for real-time communication, and is designed to work seamlessly on both web and mobile platforms.

## Live Demo
You Can check live demo at **[Visit Here](https://convocube.online/)**
- Register Your Profile
- Invite your Friends
- Enjoy your conversations in ConvoCube

## Features

- **Real-time Chat**: Users can send and receive messages instantly using Socket.io for real-time communication.
- **Group Chat**: Users can create, join, and manage groups for group chats.
- **Admin Dashboard**: Admins can log in to manage users, chats, and messages.
- **Notifications**: The app provides notifications for new messages and group updates.

## Tech Stack

- **Frontend**: React.js, Redux, React Router, Socket.io, ShadCN UI, TailwindCSS
- **Backend**: Node.js, Express, MongoDB
- **Real-time Communication**: Socket.io
- **Styling**: CSS, Styled-components (optional), TailwindCSS
- **Authentication**: JWT (JSON Web Tokens)

## Folder Structure
- **`src/`**: Contains all the frontend React code.
- **`components/`**: Reusable UI components.
- **`pages/`**: Page-level components such as Home, Login, etc.
- **`redux/`**: Redux slices and actions for state management.
- **`socket/`**: Handles Socket.io connections and events.
- **`constants/`**: Stores constants like URLs, events, etc.
- **`api/`**: Contains API calls and integrations with the backend.

## How to Contribute

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your Changes
4. Commit your changes:
   ```bash
   git commit -am 'Add new feature'
   ```
5. Push to the branch
   ```bash
   git push origin feature-name
   ```
6. Create a new Pull Request.
