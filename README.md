# Text_Summarizer

Text_Summarizer is a simple Python project designed to summarize long text articles using Natural Language Processing (NLP) techniques. This project utilizes the NLTK library to process and summarize the text, and Streamlit for the user interface.

## Features

- **Text Summarization**: Enter text manually and receive a concise summary.
- **Interactive UI**: Simple and user-friendly interface powered by Streamlit.
- **NLP Processing**: Uses NLTK for tokenization, stopwords removal, and frequency-based summarization.

## Installation

To set up the Text_Summarizer project, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yaminibhole/Text_Summarizer.git
2. **Install the Required Dependencies**:
   pip install -r requirements.txt
   
## Usage
To run the Text_Summarizer application, use the following command: streamlit run app.py

## How It Works
- **Input Text**: The user inputs the text they want to summarize into the provided text area.
- **Text Preprocessing**: The text is cleaned to remove unwanted characters and stopwords.
- **Frequency Table Creation**: A frequency table of words is created after tokenization and stopwords removal.
- **Sentence Scoring**: Each sentence is scored based on the words it contains and their frequencies.
- **Summary Extraction**: The top sentences with the highest scores are selected to form the summary.

## Acknowledgements
- **NLTK**: Natural Language Toolkit for NLP processing.
- **Streamlit**: Framework for creating interactive web applications.

