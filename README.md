# SmartMCQ

## MCQ Generation from Text using T5 and NLP

## Overview

This project implements a system that automatically generates multiple-choice questions (MCQs) from a given input text using Natural Language Processing (NLP) and Machine Learning techniques. The system leverages pre-trained models like T5 (Text-to-Text Transfer Transformer) and Sense2Vec for extracting relevant information from the input text and generating meaningful questions. This tool is useful for educators, content creators, and anyone interested in automatically generating quizzes or assessments.

## Features

- **Text Input**: Users can input text directly or upload a file (PDF or TXT format).
- **Question Generation**: The system processes the input text and automatically generates MCQs based on the text's context and keywords.
- **Answer Choices**: For each MCQ, the system generates distractors using semantic similarity with the correct answer.
- **Validation**: The system displays the correct answer to validate user-selected answers.
- **Randomization**: Questions are generated randomly from the text to ensure diverse content.

## Technologies Used

- **Flask**: Python web framework used for building the web application.
- **spaCy**: Advanced NLP library used for text processing.
- **T5**: Pre-trained transformer model used for question generation.
- **Sense2Vec**: A model used for word embeddings and sense disambiguation to generate semantic distractors.
- **NLTK**: Natural Language Toolkit for basic text processing like tokenization and keyword extraction.
- **PyTorch**: Deep learning library for managing the neural network operations.
- **Transformers**: Library for working with transformer-based models like T5.
- **Gensim**: For topic modeling, document indexing, and similarity retrieval.
- **Levenshtein Distance**: Used for calculating string similarity.


