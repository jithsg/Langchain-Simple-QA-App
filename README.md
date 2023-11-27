# Langchain-Simple-QA-App

This Streamlit application leverages OpenAI's GPT models via the LangChain library to provide a simple and interactive Question-Answering interface.
Description

The LangChain Simple QA App is designed to showcase how you can integrate OpenAI's powerful language models into a user-friendly web application. 
Users can input questions, and the app, powered by OpenAI's API, returns answers in real-time.
Features
- Interactive question input
- Real-time AI-powered responses
- Easy-to-use web interface

## Installation

To run this application locally, you need to have Python installed on your system. Follow these steps to set up the app:

    Clone the Repository:

    bash

git clone [URL to your repository]
cd [repository name]

Set Up a Virtual Environment (Optional but recommended):

bash

python -m venv venv
source venv/bin/activate  # On Unix or MacOS
venv\Scripts\activate     # On Windows

Install Dependencies:


pip install -r requirements.txt

Environment Variables:

    Create a .env file in the root directory.
    Add your OpenAI API key to the .env file:

    plaintext

        OPENAI_API_KEY=yourapikey

        Note: Never commit your .env file to version control.

Usage

To run the Streamlit app:

bash

streamlit run app.py

Navigate to http://localhost:8501 in your web browser to interact with the application.
Contributing

Contributions, issues, and feature requests are welcome. Feel free to check issues page if you want to contribute.
License
