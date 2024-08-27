# Text Summarizer using NLP

This project implements an extractive text summarization system using Natural Language Processing (NLP) techniques. The system compares frequency-based and k-means clustering approaches to generate optimal summaries from input text.

## Project Overview

The goal of this research internship project was to address the growing problem of information overload by developing an effective automatic text summarization technique. The project focuses on extractive summarization, which involves selecting and concatenating the most important sentences from the original document based on statistical and linguistic features.

## Features

- Frequency-based summarization technique
- K-means clustering-based summarization technique
- Comparison of both approaches in terms of:
  - Summary coherence
  - Keyword/topic representation
  - Implementation complexity


## Usage

Open the Colab notebook:
[Text Summarizer Notebook](https://colab.research.google.com/drive/1T-6TJXF9b0V83TGxyoq4rUL4RYBdIm8c?usp=sharing)

Follow the instructions in the notebook to run the summarization algorithms and compare their results.

## Methodology

1. **Preprocessing**: Remove stop words from input text (no stemming applied).
2. **Frequency-based approach**: 
   - Calculate term frequency and keyword frequency
   - Score sentences based on keyword presence
   - Extract top-scoring sentences
3. **K-means clustering approach**:
   - Cluster similar sentences
   - Order clusters and select representative sentences

## Results

- Frequency-based technique:
  - More coherent summaries
  - Challenging to extract important sentences with keywords
  - Lower implementation complexity
- K-means clustering:
  - Potentially disjointed summaries due to out-of-order extraction
  - Better at extracting keyword-related topics
  - Higher implementation complexity

## Limitations and Future Work

- Short inputs may result in errors due to insufficient word frequency
- Foreign language inputs are supported but may require additional evaluation
- Improper URLs or illogical text inputs may cause errors or meaningless summaries
- Future work could explore:
  - Abstractive summarization techniques
  - Domain-specific summarization (e.g., news articles, scientific papers)
  - Integration of topic modeling

## Contributors

- Ashutosh Rana
- Dr. Deepak Kumar Singh (Supervisor)

## Acknowledgments

Special thanks to Dr. Deepak Kumar Singh for his guidance and support throughout this research internship at the Indian Institute of Information Technology, Lucknow.
