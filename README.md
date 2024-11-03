# Sentiment Analysis with VADER and roBERTa 

## Overview

This project performs sentiment analysis using two different methods: **VADER** from the Natural Language Toolkit (NLTK) and **RoBERTa** from the Hugging Face Transformers library. The goal is to compare the results from both methods on a set of sample text data. 

## Objectives

- Analyze sentiment of text data using VADER, which is a rule-based model tailored for social media text.
- Analyze sentiment of text data using RoBERTa, a transformer-based model that leverages deep learning for sentiment classification.
- Compare and contrast the results obtained from both models.

## Installation

To run this project, you will need Python installed along with the following libraries:

- **pandas**: For data manipulation and analysis.
- **nltk**: For natural language processing, particularly VADER.
- **transformers**: For using the RoBERTa model.
- **torch**: Required for running the RoBERTa model.

You can install these libraries using pip. Here’s how to do it:

```bash
pip install pandas nltk transformers torch


```

## Setup

Before running the script , download the VADER lexicon, which is necessary for the NLTK's sentiment analyzer. You can do this by running the following commands in a Python interpreter or in your script:

```bash

import nltk
nltk.download('vader_lexicon')

```

## Usage
Clone the Repository: Clone the project repository to your local machine using the following command:

```bash

git clone https://github.com/your_username/sentiment_analysis_project.git
Navigate to the Project Directory: Change into the project directory:

```

```bash

cd sentiment_analysis_project

```


Run the Script: Execute the main.py script to perform sentiment analysis:

```bash

python main.py

```

## Conclusion
This project demonstrates how to use both VADER and RoBERTa for sentiment analysis. By comparing the results from these two approaches, you can better understand the strengths and weaknesses of each method in analyzing sentiments in text.

## License
This project is licensed under the MIT License. 




