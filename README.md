# Transformer Summazier

<img width="1373" alt="transformer" src="https://github.com/user-attachments/assets/71457942-3ef8-4493-97ab-df2b5f58dc5a">



Summarization is an important task in natural language processing and could be useful for a consumer enterprise. For example, bots can be used to scrape articles, summarize them, and then you can use sentiment analysis to identify the sentiment about certain stocks. Who wants to read an article or a long email today anyway, when you can build a transformer to summarize text for you? Let's get started.

This model is heavily based on attention and does not rely on sequences, which allows for parallel computing.

# Introduction
This projects aims at exploiting the transformers to make a summarizer, it has two files, `Transformer_Summarizer.ipynb` and `utils.py` along with two folders `data` and `images`.

The `data` folder consists of the data on which the transformer is trained and the `images` folder has various images of the transformer architecture.

`Transformer_Summarizer.ipynb` consists of the implementation of the summarizer from scratch and uses some utilites from the `utils.py`.

# Objectives Accomplished in the Project

- Implement DotProductAttention
- Implement Causal Attention
- Understand how attention works
- Build the transformer model
- Summarization

# Table of Contents

- 1 - Importing the Dataset
- 2 - Preprocess the Data
- 3 - Positional Encoding
- 4 - Masking
- 5 - Self-attention
    - 5.1 - scaled_dot_product_attention
- 6 - Encoder
    - 6.1 - Encoder Layer
    - 6.2 - Full Encoder
- 7 - Decoder
    - 7.1 - Decoder Layer
    - 7.2 - Full Decoder
- 8 - Transformer
    - 8.1 - Transformer
- 9 - Initialize the Model
- 10 - Prepare for Training the Model
- 11 - Summarization
    - 11.1 - next_word
- 12 - Training the Model
- 13 - Summarize some sentences!
