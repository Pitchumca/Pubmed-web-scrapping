PubMed Article Summarization and Q&A System
Overview

This project allows users to search for PubMed articles based on a query, summarize the abstracts of the found articles, generate answers to questions based on the summary, and convert the summary to an audio file.
Features

    Search PubMed Articles: Enter a query to search for relevant PubMed articles.
    Summarize Abstracts: Summarize the abstracts of the found articles.
    Question Answering: Ask questions based on the summary and get answers.
    Text-to-Speech: Convert the summary to an audio file and play it.

Requirements

    transformers
    datasets
    requests
    gtts
    pydub
    ipywidgets

Installation

Install the required libraries:

bash

!pip install transformers datasets requests gtts
!pip install pydub ipywidgets

Usage

    Run the code in a Jupyter notebook or Google Colab.
    Enter your search query in the provided text input field.
    Click the "Search" button to search for PubMed articles.
    The number of articles found, summaries, and audio playback of the summary will be displayed.
    Enter a question in the provided text field.
    Click the "Ask" button to get an answer based on the summary.

Code

python

# Include the full provided code here for reference.

Example

    Enter machine learning in healthcare as a query.
    Click Search.
    The system fetches articles, summarizes abstracts, and plays the audio summary.
    Enter a question like What are the applications of machine learning in healthcare?.
    Click Ask to get the answer.

License

This project is licensed under the MIT License.
