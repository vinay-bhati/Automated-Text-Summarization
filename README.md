# Text Summarization Using Fine-tuned LLMs 📝

This repository contains code for performing abstractive text summarization using three fine-tuned Large Language Models (LLMs): T5, PEGASUS, and BART. Abstractive summarization involves understanding the main ideas of a text and expressing them in new words. Below, we outline the steps involved in the process and discuss how we improved upon the base models.

## Introduction 🚀  
In this project, we delve into the world of text summarization using fine-tuned Large Language Models (LLMs) such as T5, PEGASUS, and BART. Text summarization involves condensing a large body of text into a shorter version while retaining its core meaning and main ideas.

## What is Text Summarization? 🤔
Text summarization is the process of distilling the main points from a piece of text to create a concise summary. It can be categorized into extractive, where sentences are selected and rearranged, and abstractive, where the summary is generated in a novel way.
 
## Summarization Types 📚
There are two types of summarization techniques:
1. **Extractive Summarization**: Involves identifying and extracting key phrases, sentences, or segments directly from the original text to form a condensed version. It's akin to highlighting parts of the text that are deemed most informative or relevant.
2. **Abstractive Summarization**: Goes beyond mere extraction by understanding the main ideas and expressing them in new words. It's akin to reading a text and then explaining it in one's own words. This is the technique used in this project.

## Dependencies: 📦

• **Python Libraries**: NumPy, Pandas, Seaborn, Matplotlib  
• **Deep Learning Framework**: PyTorch  
• **Model-specific Libraries**: Transformers  

## Data Preprocessing and EDA 📊
We begin with data preprocessing and exploratory data analysis (EDA) to prepare our dataset for training.
### Steps:
• **Import Libraries**: Import necessary libraries including pandas, numpy, seaborn, matplotlib, torch, and others.  
• **Read Data**: Read the dataset (news_summary.csv) into a pandas DataFrame.  
• **Data Cleaning**: Remove any null values and convert text to lowercase for uniform processing.  
• **Data Analysis**: Analyze the length distribution of headlines, text, and condensed text (ctext).  
• **Prepare Dataset**: Merge headlines and condensed text to create the input-output pairs for summarization.  
• **Tokenization**: Tokenize the data using appropriate tokenizers for each LLM.  

## Model Architecture: 🏗️
We employ the following architecture and models:

• **T5 (Text-To-Text Transfer Transformer)**: Utilized for abstractive summarization.  
• **PEGASUS**: Explored for abstractive summarization.  
• **BART**: Utilized for abstractive summarization.  

## Future Work: 🚀

• Experiment with different pre-trained models and architectures.  
• Explore domain-specific fine-tuning for improved summarization in specific domains.  
• Incorporate user feedback mechanisms to enhance the quality of generated summaries.  
## Conclusion: 🎯
Text summarization using fine-tuned LLMs presents a promising approach to condense large volumes of text while preserving essential information. By leveraging advanced language models, we can generate concise and coherent summaries that aid in information retrieval and understanding.
