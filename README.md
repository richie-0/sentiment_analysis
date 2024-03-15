# Sentiment Analysis on Amazon Product Reviews

# This Jupyter notebook performs sentiment analysis on Amazon product reviews using spaCy and TextBlob. It analyzes the sentiment of customer reviews and visualizes the results using word clouds.

## Table of Contents

# - [Introduction](#introduction)
# - [Installation](#installation)
# - [Preprocessing](#Preprocessing)
# - [Polarity](#polarity)
# - [Word Clouds](#word-clouds)
# - [Review Similarity](#review-similarity)

## Introduction

# The notebook begins by reading a CSV file containing Amazon product reviews. It then proceeds to clean the data, selecting only the necessary columns (these can be changed) for sentiment analysis and handling any missing values.

## Installation

# To run this notebook, you'll need to install the following Python packages:

# - [spaCy](https://spacy.io/usage)
# - [TextBlob](https://textblob.readthedocs.io/en/dev/)
# - [pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html)
# - [numpy](https://numpy.org/install/)
# - [matplotlib](https://matplotlib.org/stable/users/installing.html)
# - [wordcloud](https://pypi.org/project/wordcloud/)

# You can install these packages using pip:

# ```
# pip install spacy textblob pandas numpy matplotlib wordcloud
# ```

# Additionally, you'll need to download the English language model for spaCy:

# ```
# python -m spacy download en_core_web_md
# ```

## Preprocessing

# The selected columns are preprocessed to remove punctuation and stop words, and the text is lemmatized using spaCy's English language model.

## Polarity

# The notebook calculates the polarity and subjectivity of each review using TextBlob's sentiment analysis capabilities. Positive, negative, or neutral sentiment is determined based on the polarity score.

## Word Clouds

# Word clouds are generated to visualize the most common positive and negative words in the reviews. This provides an intuitive representation of the sentiment expressed by customers.

## Review Similarity

# Finally, the notebook calculates the similarity between two selected reviews using spaCy's similarity scoring. This metric helps identify reviews with similar content or sentiment.
