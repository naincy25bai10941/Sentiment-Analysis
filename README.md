# Sentiment-Analysis
In this project, I built a simple sentiment analysis system using Python. It processes text from a file, removes unnecessary words, identifies emotions, and determines whether the sentiment is positive, negative, or neutral. The results are also shown using a graph.
## Sentiment Analysis using Python (NLP Project)
## Project Overview
This project performs sentiment analysis on text data
using Natural Language Processing (NLP) techniques. It
reads a text file, processes the text, identifies
emotions, and determines whether the overall
sentiment is positive, negative, or neutral.
The project also visualizes the emotions detected in the
text using a bar graph.
## Objective
The main objecive of this project is to understand how
text data can be analyzed using basic NLP techniques
and to classify the sentiment of the given text.
## Features
* Converts text into lowercase
* Remove punctuation
* Tokenizes text into words
* Remove stopwords
* Performs lemmatization
* Detects emotions using a custom dataset
* Classifies sentiment using VADER
* Displays emotion distribution using a graph
## Technologies Used
* Python
* NLTK (Natural Language Toolkit)
* Matplotlib
* Collections (Counter)
## Files in the Project
* ‘Sentiment_analysis.py’ – Main Python
code
* ‘read.txt’ – Input text file
* ‘emotions.txt’–Word-emotion mapping file
* ‘graph.png’ – Output graph generated after execution
## How to Run the Project
Step 1: Install required libraries

pip install nltk matplotlib

Step 2: Download NLTK data (run once)

Open Python and run: python

import nltk

nltk.download('punkt')

nltk.download('punkt_tab')

nltk.download('stopwords')

nltk.download('wordnet')

nltk.download('vader_lexicon')

Step 3: Run the program

Python Sentiment_analysis.py
## Output
* List of detected emotions
* Count of each emotion
* Overall sentiment (Positive / Negative / Neutral)
* Bar graph showing emotion distribution
