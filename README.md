> I'm **Saiyam Jain** from **IIT (BHU) Varanasi, UP, India**

# Chit-Chat: Frontend - Real-Time Chat, Voice, and Video Calling Platform

Chit-Chat is a real-time chatting platform with voice and video calling features, built using React.js and Vite. This README will guide you through the project, its dependencies, and how to set it up locally.

## Dependencies

Chit-Chat relies on several packages to provide its functionality. Here's a list of the packages used in this project:

- `@emoji-mart/data`: Provides emoji data for the chat.
- `@emoji-mart/react`: Allows users to select emojis for messages.
- `@emotion/cache`, `@emotion/react`, `@emotion/styled`: Used for managing styles in the project.
- `@hookform/resolvers`: Provides form resolvers for React Hook Form.
- `@iconify/react`: Used for displaying icons in the application.
- `@mui/lab`, `@mui/material`: Material-UI components for the user interface.
- `@reduxjs/toolkit`, `redux`, `redux-persist`: For state management and persistence.
- `axios`: Handles HTTP requests in the project.
- `emoji-mart`: An emoji picker component.
- `framer-motion`: Used for animations.
- `phosphor-react`: Provides a set of icons.
- `react`, `react-dom`: The core React libraries.
- `react-helmet-async`: Manages document head tags.
- `react-hook-form`: A library for form validation.
- `react-lazy-load-image-component`: Used for lazy-loading images.
- `react-redux`: Provides Redux bindings for React.
- `react-router-dom`: Handles routing in the application.
- `react-scripts`: Configuration and scripts for React development.
- `socket.io-client`: Enables real-time communication via WebSocket.
- `web-vitals`: Monitors the web application's performance.
- `yup`: A schema validation library.
- `zego-express-engine-webrtc`: A library for real-time communication and video calling.

## Setup and Run Locally

To run Chit-Chat locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/SaiRev0/Chit-Chat-Frontend.git
   cd Chit-Chat
   ```

2. Create a `.env` file and add your Backend URL, Zegocloud APPID and SERVER SECRET:

   ```env
   VITE_appID=your_app_id
   VITE_server =your_server_secret
   VITE_Backend=backend_url
   ```

3. Install the project dependencies using npm or pnpm:
   `npm install`
   or
   `pnpm install`
   <br/>

4. Start the Vite development server:
   `npm run dev`
   or
   `pnpm run dev`
   <br/>

**Make sure to start your backend server before starting the frontend server**

---

# Chit-Chat: Backend - Real-Time Chat, Voice, and Video Calling Platform

Chit-Chat is a real-time chatting platform that also supports voice and video calling. The frontend is built with ReactJS using Vite, and the backend is developed using Node.js, Express, and MongoDB as the NoSQL database.

## Project Dependencies

The project utilizes the following packages for various functionalities:

- `bcryptjs`: Used for hashing and salting user passwords.
- `body-parser`: Middleware for parsing incoming request bodies.
- `cookie-parser`: Middleware for parsing cookies.
- `cookie-session`: Middleware for session management using cookies.
- `cors`: Enables Cross-Origin Resource Sharing, allowing the frontend to communicate with the backend.
- `dotenv`: Load environment variables from a .env file.
- `express`: A minimal and flexible Node.js web application framework.
- `express-mongo-sanitize`: Helps prevent MongoDB NoSQL injection.
- `helmet`: Enhances security by setting various HTTP headers.
- `jsonwebtoken`: Used for creating JSON Web Tokens (JWT) for authentication.
- `mongoose`: An ODM library for MongoDB, simplifying database interactions.
- `socket.io`: Enables real-time, bidirectional communication between the server and clients.
- `xss-clean`: Protects against cross-site scripting (XSS) attacks.

## Database System Design

## Setup and Run the Project Locally

To set up and run the project on your local machine, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/SaiRev0/Chit-Chat-Backend-Server.git
   cd Chit-Chat-Backend
   ```

2. Create a `.env` file in the project root directory and add the following variables:

   ```env
   PORT="Set the port number for the server"
   DATABASE_PASSWORD="Your MongoDB database password"
   DATABASE="Your MongoDB database URL"
   JWT_SECRET="A secret key for JWT token generation"
   ZEGO_APP_ID="Zegocloud App ID for voice and video calling"
   ZEGO_SERVER_SECRET="Zegocloud Server Secret for authentication"
   ```

3. Install project dependencies `npm install`

4. Start the server with nodemon: `npm start` or without nodemon: `node server.js`

> The project should now be up and running locally, allowing you to chat, make voice calls, and video calls in real-time

---

> That's it! You can now access Chit-Chat in your web browser at the specified address and enjoy real-time chatting, voice, and video calling features.
