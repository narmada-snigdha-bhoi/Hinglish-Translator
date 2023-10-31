# Hinglish-Translator

This repository contains a python script which demonstrates a simple Hinglish(a mix of Hindi and English) translator. The script uses the spaCy library to identify nouns in English sentences. Then it uses the Google Translate API to perform the translation from English to Hindi. Finally, it replaces the translated nouns with the original English nouns.


## Libraries Used

*  spaCy: It is an open-source library for Natural Language Processing (NLP) in Python. It is designed to be efficient and user-friendly, allowing developers to perform a wide range of NLP tasks. spaCy provides pre-trained models for various languages, including English, which can be used for tasks such as tokenization, part-of-speech tagging, named entity recognition, dependency parsing, and more. It also allows for easy integration with deep learning frameworks and other libraries, making it a popular choice for NLP tasks.
    *  Key features of spaCy include:
        *  Fast and efficient processing of text data.
        *  Pre-trained word vectors and models for multiple languages.
        *  Support for advanced NLP tasks like entity linking and text classification.    


*  googletrans: It is a Python library that provides a simple interface to Google's Translate API. It allows users to easily perform language translation tasks. This library is particularly useful for translating text from one language to another in applications or scripts. It's important to note that using this library requires an internet connection as it interacts with Google's online translation service.

    *  Key features of googletrans include:
        *  Easy-to-use API for translating text between languages.
        *  Supports a wide range of languages for translation.
        *  Provides options for specifying the source and target languages.

        
## Usage
*  Ensure that you have installed the required libraries and downloaded the SpaCy model as instructed in the Requirements section.
*  Run the script.
*  Enter the english sentence you want to translate in the input section.
*  The translated Hinglish text will be printed as the output.
