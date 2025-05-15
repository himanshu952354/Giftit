# Gift Recommender ChatBot

A simple AI-powered gift recommendation chatbot built with Express.js and Google's Gemini API.

## Features

- Get personalized gift suggestions based on person description or occasion
- Clean and intuitive user interface
- Real-time response with loading indicators
- Error handling and validation

## Setup and Installation

1. Clone this repository
2. Install dependencies:
   ```
   npm install
   ```
3. Create a `.env` file in the root directory with your Gemini API key:
   ```
   GEMINI_API_KEY=your_api_key_here
   ```
4. Start the development server:
   ```
   npm run dev
   ```

## Usage

1. Open your browser and go to `http://localhost:3000`
2. Enter a description of the person or occasion in the input field
3. Click the "Get Gift Suggestion" button or press Enter
4. View the AI-generated gift recommendation

## Technologies Used

- Express.js - Backend server
- Google Gemini API - AI text generation
- Bootstrap - Frontend styling
- Axios - HTTP requests

## Development

For development with auto-reload:
```
npm run dev
```

For production:
```
npm start
``` 