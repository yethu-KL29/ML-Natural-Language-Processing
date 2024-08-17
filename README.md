# NLP Yelp Reviews Classification

## Overview

This project involves classifying Yelp reviews into 1-star or 5-star categories based on the text content of the reviews. The project utilizes natural language processing (NLP) techniques, including `CountVectorizer` and `TfidfTransformer`, integrated into a pipeline to preprocess the text data and train a classifier.

## Project Components

- **CountVectorizer:** Converts raw text into a matrix of token counts.
- **TfidfTransformer:** Transforms the token counts into TF-IDF (Term Frequency-Inverse Document Frequency) scores.
- **Pipeline:** Integrates the `CountVectorizer`, `TfidfTransformer`, and a classifier into a streamlined process.
- **Classifier:** Uses an SVM (Support Vector Machine) for classification.

## Installation

To get started, you'll need to have Python installed along with the required libraries. You can install the necessary packages using pip:

```bash
pip install numpy pandas scikit-learn
