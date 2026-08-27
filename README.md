# Customer Support Call Analysis

## 📌 Project Overview

This project focuses on analyzing customer support calls using **Speech Recognition and Natural Language Processing (NLP)** techniques.

The objective is to transform customer support audio and text data into meaningful insights such as:

- Customer sentiment
- Frequently mentioned entities
- Customer complaints
- Similar customer conversations

The project demonstrates an end-to-end workflow starting from a customer support audio file and text-based customer call transcriptions.

---

## 🎯 Business Objective

Customer support teams handle a large number of calls every day. Manually listening to and analyzing these conversations can be time-consuming.

This project demonstrates how NLP and speech processing can be used to automate customer support call analysis.

The solution performs the following tasks:

1. Convert customer support audio into text.
2. Analyze the sentiment of customer conversations.
3. Calculate the number of correctly predicted positive conversations.
4. Identify named entities mentioned across customer calls.
5. Find the most frequently occurring named entity.
6. Identify the customer call most similar to a specific complaint such as **"wrong package delivery"**.
7. Analyze basic audio properties to assess compatibility for future speech recognition modeling.

---

## 🔄 Project Workflow

```text
                    Customer Support Data
                            |
              +-------------+-------------+
              |                           |
              v                           v
        Customer Audio              Call Transcriptions
              |                           |
              v                           v
       Speech-to-Text                NLP Analysis
              |                           |
              v               +-----------+-----------+
       Transcribed Text       |           |           |
                              v           v           v
                         Sentiment      NER       Similarity
                              |           |           |
                              v           v           v
                       True Positive  Most Frequent  Most Similar
                                      Entity          Customer Call



## Technologies Used:

Technology	Purpose
Python	Core programming language
Pandas	Data loading and data manipulation
NLTK	Natural Language Processing
VADER	Sentiment analysis
SpeechRecognition	Speech-to-text conversion
pydub	Audio processing and metadata extraction
spaCy	Named Entity Recognition and semantic similarity
en_core_web_sm	English NLP model
Jupyter Notebook	Development environment


# Conclusion

The **Customer Support Call Analysis** project demonstrates an end-to-end approach to extracting useful insights from customer support calls.

The project combines:

**Speech-to-Text + Sentiment Analysis + Named Entity Recognition + Semantic Similarity**

to convert unstructured customer conversations into structured information that can support business decision-making.

The solution provides a foundation for developing a more advanced **AI-powered Customer Support Analytics Platform** using modern speech recognition models, transformer-based NLP, embeddings, vector databases, LLMs, and business intelligence dashboards.
