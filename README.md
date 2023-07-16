# Text Summarization

This project demonstrates how text can be summarized by selecting the most important sentences from the text. It provides a basic approach to text summarization using the intersection score between sentences.

Text from [Sky News](http://news.sky.com/story/snap-election-to-be-held-in-march-after-northern-ireland-government-collapses-10731488)

## Overview

Text summarization is a useful technique for extracting key information from large texts, such as articles, reports, or documents. The code provided in this repository showcases a simple method for text summarization using an intersection score based on shared words between sentences.

## Features

- Extracts text from a web page using web scraping techniques.
- Calculates the intersection score between sentences to measure their similarity.
- Identifies the most important sentences based on their cumulative scores.
- Generates a summary by selecting the top-ranked sentences.
- Supports customization of the number of sentences in the summary.

## Requirements

- Python 3.x
- NLTK
- BeautifulSoup
- Gensim

## Usage

To use the text summarization code, follow these steps:

1. Install the required dependencies specified in the Requirements section.
2. Run the code in a Python environment that supports Jupyter notebooks or execute the code in a Python script.
3. Provide the URL of the web page you want to summarize when prompted.
4. Specify the number of sentences you want in the summary.

## Limitations and Future Enhancements

It's important to note that the current approach to text summarization provided in this code is simplistic and may not always produce optimal results. Text summarization is a challenging task, and more advanced techniques, such as natural language processing and machine learning algorithms, can be explored to improve the quality of the summaries.

Here are some potential enhancements for future development:

- Implement more sophisticated scoring algorithms for sentence selection.
- Experiment with machine learning models, such as transformer-based models, for better summarization performance.
- Support summarization of various text formats, such as PDF or Word documents.
