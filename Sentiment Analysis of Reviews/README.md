# Sentiment Analysis of British Airways Reviews

This project focuses on performing sentiment analysis on customer reviews of British Airways. The goal is to analyze the sentiment expressed in the reviews and gain insights into the overall sentiment distribution and frequent terms used by customers.

## Data Scraping
The project involves scraping data solely from the airlinequality website to collect a significant number of customer reviews for British Airways. The data scraping process focuses on extracting the textual reviews only, disregarding other information such as ratings or additional metadata.

## Sentiment Analysis
The collected reviews are subjected to sentiment analysis using natural language processing techniques. The project utilizes the NLTK library for text processing tasks, including tokenization, lemmatization, and part-of-speech tagging. Sentiment analysis is performed using a pre-trained transformer model (such as RoBERTa) for sequence classification.

## Word Cloud and Term Extraction
To visually represent the most frequent terms in the reviews, a word cloud is generated. The project utilizes the WordCloud library to create visually appealing word clouds, with common stopwords removed. Additionally, term extraction techniques, including n-grams, are applied using the NLTK library to identify frequent word pairs or phrases in the reviews.

## Environment and Tools
- Python programming language
- tqdm library for progress bar visualization
- pandas for data manipulation and analysis
- matplotlib and seaborn for data visualization
- WordCloud library for creating word clouds
- numpy for numerical computations
- NLTK library for natural language processing tasks, including text processing and tokenization
- transformers library for utilizing pre-trained transformer models
- scipy for softmax function
- Matcher from spacy.matcher for pattern matching in text

## Instructions for Running the Project
1. Clone the project repository .
2. Open the project notebook in Google Colab.
3. Install the required libraries using the provided pip command.
4. Follow the instructions within the notebook to perform data scraping, sentiment analysis, and word cloud generation.
5. Analyze the results obtained and explore the insights from the British Airways reviews.

