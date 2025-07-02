_AI CHATBOT WITH NLP_

*COMPANY : CODTECH IT SOLUTIONS

*NAME : Grace Blessy S

*INTERN ID : CT04DG1243

*DURATION : 4 WEEKS

*MENTOR : NEELA SANTHOSH

*DESCRIPTION:

This project is a rule-based AI chatbot developed in Python that uses Natural Language Processing (NLP) to understand user inputs and respond intelligently. It is designed to simulate basic conversation by detecting user intent and selecting an appropriate response based on predefined patterns.
The chatbot reads user input, processes it using NLP techniques like tokenization and stemming, and then classifies the intent using either keywords or a simple machine learning model. Based on the identified intent, it replies with a predefined response — mimicking natural conversation.
The NLP chatbot:
Uses tokenization, stemming, and vectorization to preprocess user input
Classifies the input using a lightweight ML model or keyword matching
Generates dynamic replies from an intents JSON file
Can be trained once and reused using pickle
Runs in the terminal or optionally with a GUI

*TOOLS USED:
Library       	   Purpose
nltk	     -    NLP tasks (tokenizing, stemming, corpus loading)
scikit-learn - 	Model training (TF-IDF, Naive Bayes or SVM)
json	       -   Load intents and responses
random	-        Select random reply from matched intent
pickle	      -Save/load trained model and vocabulary

*WHAT CAN BE IMPLEMENTED:

*Data Loading and Preparation
Load intent patterns from intents.json
Tokenize and stem words using nltk

*Create a vocabulary and associate patterns with tags
Text Vectorization
Use CountVectorizer or TfidfVectorizer to convert text to numerical format

*Model Training
Train a classifier (e.g., Naive Bayes or Logistic Regression) to predict user intent
Save the model using pickle for reuse

*Chat Interface (CLI)
Accept user input in terminal
Preprocess it
Predict the intent
Generate a response from that intent

*Error Handling and Fallbacks
Add a default/fallback message when intent isn’t matched

