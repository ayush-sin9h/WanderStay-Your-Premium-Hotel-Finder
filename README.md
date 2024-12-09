# WanderStay-CHATBOT
The main goal of making "WanderStay" is to assist people in India by serving as a personalized, intelligent travel assistant for finding hotels across states and union territories
## Overview
WanderStay allows users to search for hotels in a specific state, city, or union territory by simply entering their destination.
<br>This project can significantly understand user patterns and reply with appropriate responses based on the query of the user. However, the Chatbot can only respond to specific keyword-based queries and can understand human language based on predefined patterns.
## Features
WanderStay provides the following features:
<br>1. It categorizes hotels based on region, making it easier for users to navigate their options.
<br>2. For each state or union territory, WanderStay can provide curated lists of iconic hotels with cultural or historical value (e.g., palaces in Rajasthan),eco-friendly stays or rural homestay,modern business hotels in metro cities like Mumbai, Delhi, or Bengaluru.
## Technologies Used
<br>&#8226; <b>Python</b> to build the chatbot
<br>&#8226; <b>NLTK</b> library used to build the Chatbot
<br>&#8226; <b>Scikit-learn</b> NLP library package to train the Chatbot 
<br>&#8226; <b>Streamlit</b> to create and run the application of Chatbot
<br>&#8226; <b>JSON</b> for queries data
## How To RUN
<br>To run the chatbot application, execute the following command:
<br> streamlit run ./APPLICATION.py
<br>Once the application is running, you can interact with the chatbot through the web interface. Type your message in the input box and press Enter to see the chatbot's response.
## Intents Data
<br>The chatbot's behavior is defined by the patterns.json file, which contains various tags, patterns, and responses.
## Conversation History
<br>The chatbot saves the conversation history in a CSV file (chat_log.csv). You can view past interactions by selecting the "Conversation History" option in the sidebar.
## Acknowledgements
<br>&#8226; <b>NLTK</b> for natural language processing.
<br>&#8226; <b>Scikit-learn</b> for machine learning algorithms.
<br>&#8226; <b>Streamlit</b> for building the web interface.
