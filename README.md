Gemini Healthcare Chatbot
Overview
The Gemini Healthcare Chatbot is an AI-powered chatbot designed to assist users in identifying potential health conditions based on their symptoms. It uses the Google Gemini API to simulate a conversation with the user, asking clarifying questions about their symptoms and providing a list of probable diseases along with detailed descriptions. The chatbot ensures a user-friendly experience by guiding users through a series of questions and offering personalized predictions.

This project is ideal for educational purposes, prototyping healthcare applications, or integrating into larger systems for symptom analysis.

Features
Interactive Conversations : Engages users with dynamic, question-based interactions.
Disease Prediction : Provides a list of 3 probable diseases based on user inputs.
Personalized User Data : Displays user information (name, age, email, gender) and their responses for transparency.
Responsive Design : Clean and modern UI with a responsive layout.
Session Management : Maintains user-specific data using Flask sessions.
Error Handling : Gracefully handles missing or invalid inputs.
Technologies Used
Backend : Python, Flask

AI Model : Google Gemini API (gemini-1.5-flash)

Frontend : HTML, CSS, Jinja2 Templates

Dependencies :
google-generativeai: For interacting with the Gemini API.

Flask: For building the web application.

Jinja2: For rendering dynamic templates.

Setup Instructions
Prerequisites
Python : Ensure Python 3.8 or higher is installed.

python --version

Google Gemini API Key :
Sign up for the Google AI Studio and generate an API key.

Install Dependencies :
Install the required Python libraries using pip:pip install flask google-generativeai

Steps to Run the Application
Clone the Repository :git clone https://github.com/yourusername/gemini-healthcare-chatbot.git

cd gemini-healthcare-chatbot

GOOGLE_API_KEY=your_api_key_here

Run the Flask Application :python app.py

Access the Application :Open your browser and navigate to:
