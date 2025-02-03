### Health Assistant Chatbot
This repository contains the code for a Health Assistant Chatbot built using streamlit, NLTK, sklearn, and logistic regression for natural language processing. The chatbot can answer various health-related queries based on predefined intents and responses.

## Installation
Prerequisites
Ensure you have the following installed:

Python 3.6 or later

pip package manager

## Libraries
Install the required libraries by running:

bash
pip install streamlit scikit-learn nltk
NLTK Data
To download necessary NLTK data, you can run the following within a Python environment:

python
import nltk
nltk.download('punkt')
Files
intents.json: Contains predefined intents and responses.

app.py: Main script to run the chatbot application.

Usage
## Clone the repository:

git clone https://github.com/sanjana2714/health-assistant-chatbot.git
cd health-assistant-chatbot
Ensure you have the intents.json file in the same directory as app.py.

## Run the Streamlit application:

streamlit run app.py
Open the URL provided by Streamlit in your web browser.
