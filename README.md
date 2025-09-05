# SigmaGPT

A MERN-based ChatGPT replica implemented from scratch using the OpenAI API. This project provides a full-stack chat application that leverages modern technologies to deliver a seamless and interactive user experience.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)

## Features

- **Real-time Chat**: Engage in interactive conversations with an AI-powered assistant.
- **OpenAI Integration**: Utilizes the OpenAI API to provide intelligent and context-aware responses.
- **Full-Stack Application**: A complete MERN stack implementation with a React frontend and a Node.js backend.
- **RESTful API**: A well-defined API for seamless communication between the frontend and backend.

## Technologies Used

### Backend

- **Node.js**: A JavaScript runtime for building scalable server-side applications.
- **Express**: A minimal and flexible Node.js web application framework.
- **MongoDB**: A NoSQL database for storing and managing chat history.
- **Mongoose**: An ODM library for MongoDB and Node.js.
- **OpenAI API**: For generating AI-powered responses.
- **CORS**: For enabling cross-origin resource sharing.
- **Dotenv**: For managing environment variables.

### Frontend

- **React**: A JavaScript library for building user interfaces.
- **Vite**: A fast build tool for modern web development.
- **React Markdown**: For rendering Markdown-formatted responses.
- **React Spinners**: For displaying loading indicators.
- **UUID**: For generating unique identifiers.

## Prerequisites

- **Node.js**: Ensure you have Node.js installed. You can download it from [nodejs.org](https://nodejs.org/).
- **MongoDB**: Set up a MongoDB database, either locally or through a cloud service like MongoDB Atlas.
- **OpenAI API Key**: Obtain an API key from [OpenAI](https://beta.openai.com/signup/).

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/SigmaGPT.git
   cd SigmaGPT
   ```

2. **Backend Setup**:

   ```bash
   cd Backend
   npm install
   ```

   Create a `.env` file in the `Backend` directory and add the following:

   ```env
   MONGODB_URI=your_mongodb_connection_string
   OPENAI_API_KEY=your_openai_api_key
   ```

3. **Frontend Setup**:

   ```bash
   cd ../Frontend
   npm install
   ```

## Usage

1. **Start the Backend Server**:

   ```bash
   cd Backend
   npm start
   ```

   The backend will be running at `http://localhost:8080`.

2. **Start the Frontend Development Server**:

   ```bash
   cd Frontend
   npm run dev
   ```

   The frontend will be accessible at `http://localhost:5173`.

## Project Structure

```
SigmaGPT/
├── Backend/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── .env
│   ├── package.json
│   └── server.js
├── Frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── vite.config.js
└── README.md
