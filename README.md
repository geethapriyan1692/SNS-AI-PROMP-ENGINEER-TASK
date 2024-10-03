# GENAI--PROMP-ENGINEER-TASK
## Overview
This repository contains solutions to multiple interview tasks involving Natural Language Processing (NLP), deep learning, prompt engineering, data analysis, and API integration. Below is a brief description of each task along with the key techniques and libraries used.

## 1. Natural Language Processing (NLP)
Problem: Implement a function to preprocess and tokenize text data.

## Solution:

Preprocess text by converting to lowercase, removing punctuation, and tokenizing words.
Stop words are removed to clean the data further.

## Key Libraries:

nltk for tokenization and stopwords removal.
re for regex operations.
string for punctuation handling.


## 2. Text Generation Using Pre-Trained Transformers
Problem: Build a basic text generation model using a pre-trained transformer (GPT-2).

Solution:

A transformer-based model (GPT-2) is used to generate text based on an input prompt.
The model and tokenizer are loaded from Hugging Face, and the output is decoded after generation.

## Key Libraries:

transformers for pre-trained model usage.
torch for tensor operations.


## 3. Prompt Engineering for Text Summarization
Problem: Generate text summaries using different prompt styles.

## Solution:

Using the BART model from Hugging Face, different prompts are applied to generate concise summaries.
ROUGE metric is used to evaluate the summaries against reference text.

## Key Libraries:

transformers for the summarization pipeline.
datasets and rouge_score for evaluation.

## Example Prompts:

"Summarize the following text..."
"Given the following article, provide a concise summary..."


## 4. Data Analysis: Iris Dataset
Problem: Perform data analysis on the Iris dataset.

## Solution:

The dataset is loaded, explored using descriptive statistics, and visualized with pair plots, histograms, and boxplots.
Insights are derived regarding the relationships between species and features like sepal and petal dimensions.

## Key Libraries:

pandas and numpy for data manipulation.
matplotlib and seaborn for visualization.

## 5. API Integration: Weather Data Retrieval
Problem: Fetch and display weather information using the OpenWeatherMap API.

## Solution:

The script sends a request to the OpenWeatherMap API, retrieves the weather data, and formats it for easy readability.
The script handles exceptions and invalid inputs like non-existent cities.
## Key Libraries:

requests for making API calls.

## Example Usage:
Enter city name: London
Weather Information:
City: London
Temperature: 18°C
...
