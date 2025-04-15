# Gemini-chatbot

Chat Application with Gemini API Integration -

This script powers a web-based chat interface that interacts with Google's Gemini AI model (specifically the 1.5-flash version). The application provides a responsive chat experience with features like file uploads, typing animations, and theme customization.

## Key Features

1. AI Integration: Connects to Google's Gemini API for generating responses to user queries, supporting both text and file inputs (including images).

2. Interactive UI Elements:
   - Real-time typing effect for bot responses
   - File upload capability with preview functionality
   - Light/dark theme toggle (persisted in localStorage)
   - Mobile-responsive controls

3. Chat Management:
   - Maintains conversation history in memory
   - Allows stopping ongoing responses
   - Provides a clear chat history option
   - Includes clickable suggestion prompts

4. Technical Implementation:
   - Uses modern JavaScript (ES6+) features
   - Implements AbortController for canceling requests
   - Handles base64 file encoding for uploads
   - Manages asynchronous operations with async/await

The code demonstrates good separation of concerns with distinct functions for UI updates, API communication, and event handling. It provides a smooth user experience with visual feedback during loading states and automatic scrolling to keep messages visible.
