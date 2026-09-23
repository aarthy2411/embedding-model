# Embedding Model

This project demonstrates how text embeddings can be generated using a pre-trained Sentence Transformer model and how cosine similarity can be used to compare the semantic similarity between sentences.

## Project Overview

Text embeddings convert sentences into numerical vectors that capture their semantic meaning.

In this project, the `all-mpnet-base-v2` model from Sentence Transformers is used to generate embeddings for multiple sentences. Cosine similarity is then calculated to identify sentences that have similar meanings.

## Features

- Generate text embeddings using Sentence Transformers
- Use the `all-mpnet-base-v2` pre-trained model
- Convert sentences into numerical vectors
- Calculate cosine similarity between sentences
- Identify semantically similar sentences
- Display embedding dimensions and similarity scores

  ## Project Workflow

```text
Input Sentences
       ↓
Load Pre-trained Sentence Transformer Model
       ↓
Generate Sentence Embeddings
       ↓
Convert Sentences into Numerical Vectors
       ↓
Calculate Cosine Similarity
       ↓
Compare Similarity Scores
       ↓
Identify Similar Sentences
       ↓
Display Results
```

## Technologies Used

- Python
- Sentence Transformers
- Scikit-learn
- Cosine Similarity
- `all-mpnet-base-v2`

## Installation

Install the required Python libraries using:

```bash
python -m pip install sentence-transformers scikit-learn
```


## How It Works

The project follows these steps:

A list of sentences is provided as input.
The Sentence Transformer model is loaded.
Each sentence is converted into a numerical embedding.
The embedding dimension is displayed.
Cosine similarity is calculated between the sentence embeddings.
Sentences with a similarity score greater than 0.7 are displayed.

## Example Sentences

The project compares sentences such as:

I enjoy coding in Python.
I love programming in Python.
Python is my favorite programming language.
The weather is very hot today.
It is raining heavily outside.
I went to college this morning.
My college has many computer science students.
<img width="610" height="696" alt="image" src="https://github.com/user-attachments/assets/c443958a-c26e-460e-87db-7dbeccc936ca" />


## Model Used

The project uses:

all-mpnet-base-v2

This model is provided through the Sentence Transformers library and is used to generate meaningful sentence-level embeddings.

## Applications

Text embeddings and semantic similarity are commonly used in:

Semantic Search
Recommendation Systems
Document Similarity
Question Answering
Chatbots
Retrieval-Augmented Generation (RAG)
Text Clustering
Information Retrieval

## Author

Aarthy V
