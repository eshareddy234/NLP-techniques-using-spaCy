## Natural Language Processing Techniques using spaCy 

This notebook explains NLP techniques using python's library - spaCy

### Contents 

1. About spaCy  
2. Installation  
3. Dataset Preparation for spaCy  
4. Tokenization - Word and Sentences  
5. Text Cleaning - Stopwords, Punctuations, Lemmatization  
6. Dependency Parsing  
7. Word Vector Notations  

### 1. About spaCy 

spaCy is a free, open-source library for advanced Natural Language Processing (NLP) in Python. It's designed specifically for production use and helps you build applications that process and "understand" large volumes of text. It can be used to build information extraction or natural language understanding systems, or to pre-process text for deep learning. Following are the key features of spaCy : 

- Non-destructive tokenization
- Named entity recognition
- Support for 34+ languages
- 13 statistical models for 8 languages
- Pre-trained word vectors
- Easy deep learning integration
- Part-of-speech tagging
- Labelled dependency parsing
- Syntax-driven sentence segmentation
- Built in visualizers for syntax and NER
- Convenient string-to-hash mapping
- Export to numpy data arrays
- Efficient binary serialization
- Easy model packaging and deployment
- State-of-the-art speed
- Robust, rigorously evaluated accuracy  

With so many features inbuilt, spaCy is considered as one of the powerful NLP library. 

### 2. Installation 

To install spaCy, two steps are required, 

2.1 Install the spaCy source using pip command

    pip install spacy

2.2 Download the spacy pre-trained and annotated models  

    python -m spacy download en_core_web_sm  
    
### 3. Dataset Preparation  

We first load the required libraries and prepare the data for spaCy usage.  We will load the spacy models (which were downloaded duing the installation step) and create an object "nlp". 
