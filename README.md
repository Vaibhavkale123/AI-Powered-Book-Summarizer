# AI-Powered Book Summarizer App

This is a web application that uses Flask for the backend and React.js for the frontend to provide an AI-powered book summarization service. The app allows users to enter text, and then generates a concise summary of the content.

## Features

- User-friendly interface for uploading books or text for summarization
- Utilizes Groq AI api to generate accurate and concise summaries
- Responsive design for seamless user experience on different devices

## Technologies Used

- Flask: Python-based web framework for the backend server
- React.js: JavaScript library for building interactive user interfaces
- HTML, CSS, and JavaScript for frontend design and functionality

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/Vaibhavkale123/AI-Powered-Book-Summarizer.git
   ```

2. Install dependencies for the backend (Flask):
   ```
   cd Book Summary app
   pip install -r requirements.txt
   ```

3. Install dependencies for the frontend (React.js):
   ```
   cd client
   npm install
   ```

4. Start the backend server:
   ```
   cd Book Summary app 
   python api.py
   ```

5. Start the frontend development server:
   ```
   cd client
   npm start
   ```

6. Open your browser and go to `http://localhost:3000` to use the AI-Powered Book Summarizer app.

## Usage

1. Enter text into the input field.
2. Click the "Send" button to generate a summary of the content.
3. View the summarized text on the screen.
4. Select Qestions and get answer.


## Screenshot

![Home Screenshot](/screenshot/summary.png)

## Acknowledgements

- Special thanks to the developers of [Book Cover API](https://github.com/w3slley/bookcover-api) for providing book cover API.
- This project utilizes Utilizes Groq AI api for text summarization.
