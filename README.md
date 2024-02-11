# Q&A Chatbot Project

## Project Overview
This repository hosts the Q&A Chatbot project, an interactive application designed using Streamlit and powered by OpenAI's language model. The chatbot is capable of understanding and responding to a wide range of user queries, showcasing the integration of advanced natural language processing techniques.

<img width="650" alt="image" src="https://github.com/vishal363/QA-Chatbot-using-LLM/assets/71640603/f332dd87-fa52-4f36-861e-e98d3eb3eda6">

## Key Features
Chatbot Interface: Built using Streamlit, the chatbot provides a user-friendly interface for real-time question-answering.
OpenAI Integration: Utilizes OpenAI's GPT-3.5-turbo model for generating accurate and contextually relevant responses.
Environment Variable Management: Implements dotenv for secure API key management.
Interactivity: Features an input field for queries and a submission button, with responses displayed instantly.

## Technologies Used
Python
Streamlit
OpenAI's GPT-3.5-turbo model
dotenv for environment variable management

## Repository Contents
chatbot_app.py: Main Python script for the Streamlit application.
.env: (Not included for security) File to store environment variables such as the OpenAI API key.
requirements.txt: List of Python packages required to run the application.
README.md: This file, providing a comprehensive overview of the project.

## Getting Started
To run the Q&A Chatbot locally:

Clone the repository.
Install Python and the required packages: pip install -r requirements.txt.
Set up an .env file with your OpenAI API key.
Launch the Streamlit app: streamlit run chatbot_app.py.

## How to Use
Enter your question in the input field and click 'Ask the question' to get a response from the chatbot.
