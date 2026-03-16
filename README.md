# DataMining-Project

# Overview
This project performs text mining and natural language processing (NLP) on song lyrics from the rapper Eminem.
The goal is to analyze the lyrical content using techniques such as data cleaning, TF-IDF analysis, and n-gram extraction to discover patterns, frequently used terms, and linguistic characteristics in the lyrics.

# Dataset
The dataset consists of a collection of song lyrics stored in a text file: eminem_lyrics.txt
Each song contains:
 - Title
 - Full lyrics

# Technologies Used
-Python
-Google Colab
-pandas
-NLTK
-spaCy
-scikit-learn
-matplotlib

# Project Steps
1. Data Cleaning & Preprocessing

The lyrics are cleaned and prepared for analysis using:
 - Tokenization
 - Stopword removal
 - Additional custom stopwords
 - Text normalization
 - Word extraction

2. TF-IDF Analysis

TF-IDF (Term Frequency–Inverse Document Frequency) is used to identify important words in each song relative to the whole dataset.
This helps highlight:
 - Distinctive vocabulary
 - Song-specific keywords
 - Frequently emphasized terms
   
3. N-Gram Analysis
The project also extracts n-grams (specifically trigrams) from the lyrics to identify common word sequences.
This reveals:
 - Repeated phrases
 - Linguistic patterns
 - Characteristic lyric structures
   
4. Visualization
Important terms and statistics are visualized using matplotlib, allowing easier interpretation of the results.

# Results
The analysis provides insights into:
 - Frequently used words in Eminem's lyrics
 - Characteristic word combinations
 - Linguistic patterns across songs

These techniques demonstrate how data mining and NLP can be applied to music lyrics.

