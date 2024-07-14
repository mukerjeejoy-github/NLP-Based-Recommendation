# NLP-Based-Recommendation
Leveraging raw textual data for recommendation-based applications and enhancing data quality through comprehensive pre-processing techniques

# Project Summary: Textual Data Processing and Similarity Analysis

## Problem Statement

This project focuses on leveraging raw textual data for recommendation-based applications and enhancing data quality through comprehensive preprocessing techniques. It consists of two main parts:

### Part I: Sentence Comparison using N-gram

The goal here is to build a probabilistic language model to recommend the most relevant sentences from a dataset. Using bigram analysis, the model compares test sentences against a training corpus to determine similarity.

### Part II: Text Preprocessing, Feature Extraction, and Similarity Analysis

1. **Text Preprocessing**:
   - Tokenization: Breaking down text into tokens (words or phrases).
   - Lowercasing: Converting all text to lowercase to ensure uniformity.
   - Stop Words Removal: Removing common words (like "the", "is", etc.) that don't contribute to the meaning.
   - Stemming: Reducing words to their root form to handle variations.
   - Lemmatization: Similar to stemming but ensures resulting words are valid by using vocabulary and morphological analysis.

2. **Feature Extraction**:
   - Using the preprocessed text, feature-rich representations are created using TF-IDF (Term Frequency-Inverse Document Frequency) for word embedding. This method captures the importance of words in the context of the dataset.

3. **Similarity Analysis**:
   - The vectorized representations from TF-IDF are used to identify and print the names of the top two words that exhibit significant similarity using a chosen similarity metric.
   - Justification is provided for the choice of similarity metric and feature design.
   - Visualization of a subset of the vector embeddings in a 2D semantic space is performed using PCA (Principal Component Analysis) for dimensionality reduction, making it suitable for visualization and analysis purposes.

## Conclusion

This project aims to demonstrate proficiency in natural language processing techniques, from initial text preprocessing to advanced feature extraction and similarity analysis. It provides insights into how language models can be applied to enhance recommendation systems and improve data relevance in textual applications.

