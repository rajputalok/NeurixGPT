
# NeurixGPT 🤖

A full-stack chat application that integrates OpenAI's GPT API to provide an intelligent conversational interface.

## 📋 Table of Contents

- Features
- Tech Stack
- Project Structure
- Prerequisites
- Installation
- Configuration
- Usage
- Development
- Build

## ✨ Features

- Real-time Chat Interface: Interactive chat UI powered by React
- GPT Integration: Seamless integration with OpenAI's GPT API for intelligent responses
- Full-Stack Architecture: Separated frontend and backend for scalability
- Responsive Design: Works across different devices and screen sizes
- Code Highlighting: Display and highlight code blocks in conversations
- Loading States: Visual feedback with spinners during API calls
- Markdown Support: Format and display markdown content in responses

## Tech Stack

### Frontend
- **React** ^19.2.0 - UI library
- **Vite** ^7.2.4 - Build tool and dev server
- **React Markdown** ^10.1.0 - Markdown rendering
- **React Spinners** ^0.17.0 - Loading indicators
- **Rehype Highlight** ^7.0.2 - Code syntax highlighting
- **UUID** ^13.0.0 - Unique identifier generation

### Languages
- JavaScript
- CSS
- HTML

### Backend
- Node.js/Express (to be configured)
- OpenAI API

## Project Structure

- Backend
  - package.json
  - server.js
  - models/
    - Thread.js
  - routes/
    - chat.js
  - utils/
    - openai.js

- Frontend
  - eslint.config.js
  - index.html
  - package.json
  - README.md
  - vite.config.js
  - public/
  - src/
    - App.css
    - App.jsx
    - Chat.css
    - Chat.jsx
    - ChatWindow.css
    - ChatWindow.jsx
    - index.css
    - main.jsx
    - MyContext.jsx
    - Sidebar.css
    - Sidebar.jsx
    - assets/
   
## Live Project
https://neurixgpt.onrender.com/

