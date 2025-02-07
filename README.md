# LLM_Workshop

# LLM Tutorial for Social Science Research

This repository contains materials for a workshop on using Large Language Models (LLMs) in social science research. The tutorial focuses on practical implementations using the `langchain` package and OpenAI's GPT-3.5-turbo model.

## Overview

The tutorial covers:
1. Introduction to generative LLMs and their applications in social science
2. Implementation of two key methods:
   - Chat completion for text annotation
   - Retrieval-Augmented Generation (RAG)

## Contents

- `LLM_Tutorial.ipynb`: Main Jupyter notebook containing the tutorial
- `data/`: Data for this tutorial is downloaded from the [Global Populism Dataset](https://populism.byu.edu/data/2019%20-%20global%20populism%20database%20(guardian%20version)).
  
## Key Topics

### Text Annotation Implementation
- Setting up OpenAI API and LangChain
- Handling text encoding and chunking
- Prompt engineering
- Chain creation and execution
- Validation using Krippendorff's alpha

### RAG Implementation
- Word embeddings
- Vector stores
- Document retrieval
- Response generation
- Performance evaluation

## Requirements

- Python packages:
  - langchain
  - openai
  - pandas
  - scikit-learn
  - dotenv
  - tiktoken
  - krippendorff
