# NLP (NATURAL LANGUAGE PROCESSING)
NLP is a branch of AI and Data Science which is concerned with providing the ability to understand and generate human language to machines. It is a field of computer science and linguistics concerned with interactions between human language and computers. It is often used in customer service to answer common questions, to understand the sentiment in text, and to categorize text. It is also used in search engines to provide relevant results for search queries.<br>
NLP is a way for computers to analyze, understand, and derive meaning from human language in a smart and useful way. By utilizing NLP, developers can organize and structure knowledge to perform tasks such as automatic summarization, translation, named entity recognition, relationship extraction, sentiment analysis, speech recognition, and topic segmentation.<br>

## How to Approach this repository
This repository is divided into 3 parts:
1. [**NLP FUNDAMENTALS**](#nlp-fundamentals) - This part deals with the basics of NLP and how to perform NLP tasks using Python.
2. **RNN** - This part deals with advanced NLP concepts and how to perform advanced NLP tasks using Python.
3. **NLP PROJECTS** - This part deals with the implementation of NLP concepts and how to perform NLP tasks using Python.

<hr>

## Environment Setup

* open command prompt in your working directory
* create a new environment in your working directory
```
conda create -p {env_name} python=3.7 -y
```
* activate the env
```
activate {env_name}/
```
* install the libraries
```
pip install -r requiremnts.txt
```
* install the nltk modules
    * open python on terminal using the following command
    ```
    python
    ```
    * import nltk library and download the modules
    ```python
    import nltk
    nltk.download()
    ```

You are all set to implement and practice NLP

<hr>

## NLP Fundamentals
1. Tokenization
> It is the process of breaking down a text paragraph into smaller chunks such as words or sentence. Token is a single entity that is building blocks for sentence or paragraph. Tokenization is also known as text segmentation or lexical analysis. Tokenization can be done by using NLTK library in python. It is a library that can be used for NLP. It contains packages to make machines understand human language and reply to it with an appropriate response. It can be used to perform tasks like tokenization, stemming, classification, tagging, parsing, etc.<br>
> **Code:** [Tokenization](Fundamentals/tokenizer.ipynb)

2. Stemming
> Stemming is the process of reducing a word to its word stem that affixes to suffixes and prefixes or to the roots of words known as a lemma. Stemming is important in natural language understanding (NLU) and natural language processing (NLP). Stemming is also a part of queries and Internet search engines. Stemming is the process of producing morphological variants of a root/base word. Stemming programs are commonly referred to as stemming algorithms or stemmers. <u>It is not neccessary that stemming generates a meaningful word</u><br>
> **Code:** [Stemming](Fundamentals/stemming.ipynb)

3. Lemmatizing
> lemmatizing is the process of converting different forms of word into a root/base word. It is similar to stemming but the only difference is that it derives a meaningfull word unlike stemming. Since it tries to derive a meaningfull word thus it takes more time than stemming. It is required in the cases in which we want semantically correct data for evaluation.
> **Code:** [Lemmatization](Fundamentals/lemmatization.ipynb)