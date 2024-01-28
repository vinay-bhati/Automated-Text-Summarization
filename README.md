# Text Summarization Using Fine-tuned LLMs 📝

This repository contains code for performing abstractive text summarization using three fine-tuned Large Language Models (LLMs): T5, PEGASUS, and BART. Abstractive summarization involves understanding the main ideas of a text and expressing them in new words. Below, we outline the steps involved in the process and discuss how we improved upon the base models.

## Introduction 🚀  
In this project, we delve into the world of text summarization using fine-tuned Large Language Models (LLMs) such as T5, PEGASUS, and BART. Text summarization involves condensing a large body of text into a shorter version while retaining its core meaning and main ideas.

## Summarization Types
There are two types of summarization techniques employed in this project:
1. Extractive Summarization: Involves identifying and extracting key phrases, sentences, or segments directly from the original text to form a condensed version. It's akin to highlighting parts of the text that are deemed most informative or relevant.
2. Abstractive Summarization: Goes beyond mere extraction by understanding the main ideas and expressing them in new words. It's akin to reading a text and then explaining it in one's own words. This is the technique used in this project.

## Data Preprocessing and EDA
We begin with data preprocessing and exploratory data analysis (EDA) to prepare our dataset for training.
### Steps:
• Import Libraries: Import necessary libraries including pandas, numpy, seaborn, matplotlib, torch, and others.  
• Read Data: Read the dataset (news_summary.csv) into a pandas DataFrame.  
• Data Cleaning: Remove any null values and convert text to lowercase for uniform processing.  
• Data Analysis: Analyze the length distribution of headlines, text, and condensed text (ctext).  
• Prepare Dataset: Merge headlines and condensed text to create the input-output pairs for summarization.  
• Tokenization: Tokenize the data using appropriate tokenizers for each LLM.  
