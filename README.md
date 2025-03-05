# Aspect-Based Sentiment Analysis

## Overview

This project focuses on `Aspect-Based Sentiment Analysis (ABSA`), which involves analyzing the sentiment of specific aspects within a given text. The project consists of two main steps:

**1. Aspect Term Extraction (ATE)** - Identifying aspect terms from a given sentence.

**2. Aspect Term Sentiment Classification (ATSC)** - Determining the sentiment associated with the extracted aspect terms.

## Project Structure

The project is divided into two separate Jupyter notebooks:

- `aspect_term_extraction.ipynb` - Implements the aspect term extraction step.

- `aspect_term_sentiment_cls.ipynb` - Performs sentiment classification on the extracted aspect terms.

## Dataset

The model is trained and evaluated on `the SemEval-2014 Task 4` dataset, which contains aspect-based sentiment annotations.

## How to Run

This project is designed to be executed on `Google Colab`. Follow these steps:

- Open Google Colab and upload the notebook files.
- Ensure all required dependencies are installed.
- Run `aspect_term_extraction.ipynb` to extract aspect terms.
- Run `aspect_term_sentiment_cls.ipynb` to classify the sentiment of extracted aspects.

## Results

- **Aspect Term Extraction (ATE):** Achieved 81.73% accuracy on the test set.
- **Aspect Term Sentiment Classification (ATSC):** Achieved 79.18% accuracy on the test set.
