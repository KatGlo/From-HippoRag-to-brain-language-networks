# From HippoRAG to Brain Language Networks
This project explores the integration of the HippoRAG framework with neural language processing networks, drawing inspiration from the hippocampal indexing theory of human long-term memory. The goal is to enhance the retrieval capabilities of large language models (LLMs) by mimicking the brain's memory mechanisms.

## Overview

HippoRAG is a novel retrieval-augmented generation (RAG) framework that synergistically combines LLMs, knowledge graphs, and the Personalized PageRank algorithm. This integration aims to emulate the distinct roles of the neocortex and hippocampus in human memory, facilitating deeper and more efficient knowledge integration. ([arxiv.org](https://arxiv.org/abs/2405.14831))

In this project, we apply the HippoRAG framework to analyze brain language networks, seeking to understand how neurobiologically inspired models can improve language comprehension and processing.

## Key Components

- **Text Cleaning and Preparation**: Functions to clean and normalize text data, ensuring consistency and readability.
- **Knowledge Base Preparation**: Splitting documents into manageable chunks to create an efficient knowledge base for retrieval tasks.
- **Embedding and Indexing**: Utilizing the SentenceTransformer model to encode the knowledge base and employing FAISS for efficient similarity search.
- **Training Data Preparation**: Generating training data by pairing queries with relevant contexts and answers, facilitating effective model training.
- **Context Retrieval**: Implementing functions to retrieve pertinent contexts based on input queries, enhancing the model's response accuracy.
- **Evaluation Metrics**: Calculating F1 Score, Precision, and Recall to assess the performance of the model's predictions.
- **Model Training**: Training the HippoRAG framework using the prepared training data to improve its retrieval and generation capabilities.

## References

- [HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models](https://arxiv.org/abs/2405.14831)
- [HippoRAG GitHub Repository](https://github.com/OSU-NLP-Group/HippoRAG)
- [The Margins of the Language Network in the Brain](https://www.frontiersin.org/articles/10.3389/fcomm.2020.519955/full)
- [Redefining Language Networks: Connectivity Beyond Localized Regions](https://www.frontiersin.org/articles/10.3389/fcomm.2020.519955/full)

## Acknowledgments

Special thanks to the developers of the HippoRAG framework and the researchers contributing to the understanding of brain language networks.

