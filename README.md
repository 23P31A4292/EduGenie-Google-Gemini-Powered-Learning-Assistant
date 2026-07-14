EduGenie - AI Powered Learning Assistant
Overview
EduGenie is a lightweight AI-powered educational assistant designed to simplify and enhance the learning experience using Generative AI. It helps students, self-learners, and educators by providing intelligent educational support.

Features
Intelligent Question Answering
Simplified Concept Explanation
AI-Powered Quiz Generation
Educational Text Summarization
Personalized Learning Path Recommendation
Technologies Used
Python
FastAPI
HTML
CSS
Google Gemini API
SQLAlchemy
SQLite
Jinja2
Project Structure
EduGenie/
│
├── app/
├── static/
├── templates/
├── README.md
├── requirements.txt
└── .gitignore
Installation
Clone the repository.

Create a virtual environment.

python -m venv venv
Activate the virtual environment.
Windows PowerShell

.\venv\Scripts\Activate.ps1
Install the required dependencies.
pip install -r requirements.txt
Create a .env file and add your Gemini API key.
GEMINI_API_KEY=YOUR_API_KEY
Run the application.
uvicorn app.main:app --reload
Open your browser and visit:
http://127.0.0.1:8000
🎥 Project Demonstration
Demo Video:
https://drive.google.com/file/d/1woIZvEFqbxmMQpPIR1t0Zm3UbPmYgQWq/view?usp=sharing

Author:
kalisetti siddhardha
