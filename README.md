# Chatbot App

A simple real-time chat app built with Node.js, Express, and Socket.io.  
Users can join chat rooms, send messages, filter bad words, and share their location.

***

## Features
- Real-time chat with multiple rooms
- User-friendly join form
- Profanity filter to block bad words
- Share your location with Google Maps links

***


## Setup

1. Clone the repo:
   ```bash
   git clone <your-repo-url>
   cd Chatbot-app
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the server:
   ```bash
   npm start
   ```
4. Open your browser at [http://localhost:3000](http://localhost:3000)

***

## Usage

- Enter your name and room on the homepage.
- Chat with others in the same room.
- Share your location if you want.
- 
***

## Folder Structure

```
Chatbot-app/
├── src/
│   ├── index.js       # Server code
│   └── utils/         # Helper functions
├── public/
│   ├── index.html     # Join form
│   ├── chat.html      # Chat page
│   ├── css/           # Stylesheet
│   └── js/            # Client JavaScript
├── package.json       # Node.js dependencies
└── README.md          # This file
```

***
- The app stores users in memory, so data resets when server restarts.
- No API keys or environment variables are required.
- For development, use `npm run dev` to auto-restart on changes.

***
