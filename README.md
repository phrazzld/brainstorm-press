# Brainstorm Press 🧠⚡

Brainstorm Press is a blogging platform with payments enabled by the Bitcoin Lightning Network. This repository contains the client and API repos as submodules, providing a higher-level overview of the project and how the client and API work together to create a cohesive application.

## Overview 🌐

The Brainstorm Press platform consists of two main components: the client and the API.

### Client

The client is built with React and TypeScript, and it provides a user-friendly interface for creating, editing, and viewing blog posts. Payments are enabled through the Bitcoin Lightning Network, allowing users to unlock premium content. The client uses technologies such as WebSocket, Zustand, and Draft JS to create a seamless experience.

**Client repository**: [brainstorm-press-client](https://github.com/phrazzld/brainstorm-press-client)

### API

The API is built with Node, Express, and TypeScript, and it manages the backend logic, handling user authentication, blog post management, and Lightning Network payments. The API uses MongoDB Atlas as its database, managed with Mongoose, and communicates Lightning invoice statuses to the client via WebSocket.

**API repository**: [brainstorm-press-express-api](https://github.com/phrazzld/brainstorm-press-express-api)

## Contributing 💡

We welcome contributions to the Brainstorm Press project! If you're interested in contributing, please visit the client and API repositories for more information on how to get started.
