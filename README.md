# Advanced Prompt Engineering for Retrieval-Augmented Generation (RAG)
This is my MSc dissertation, where I evaluated state-of-the-art fine-tuned RAG models against the proposed advanced prompt-engineered RAG system.
Link to papper: To_be_linked

## Project Overview
This repository contains the python notebooks, which contains code and results for my MSc dissertation, where I evaluate state-of-the-art fine-tuned RAG models against a proposed advanced prompt-engineered RAG system. The goal of the research is to determine whether advanced prompt engineering can outperform or match the performance of fine-tuned RAG models across diverse datasets and tasks, including open-domain and specialized retrieval challenges.

The project explores the adaptability and scalability of RAG systems using a versatile embedding model (`all-mpnet-base-v2`) and a novel prompt-engineering approach. This is evaluated on four datasets: **TriviaQA**, **PubHealth**, **ARC-C**, and **MuSiQue**.

## Key Components of the Repository

### 1. Embedding Model Evaluation (Google Colab Notebooks)
- Notebooks containing the evaluation of multiple embedding models, comparing their performance across different datasets.
- Evaluates models through **dataset-wise** and **embedding-wise** analysis using performance metrics like **Precision**, **Recall**, and **F1-Score**.
- Datasets evaluated: TriviaQA, PubHealth, ARC-C, and MuSiQue.

### 2. Advanced Prompt Engineering RAG (Google Colab Notebooks)
- Implements advanced prompt-engineering strategies to improve the performance of RAG systems.
- Compares prompt-engineered RAG to **Self-RAG**, **Speculative-RAG**, and other state-of-the-art models.
- Demonstrates the impact of well-crafted prompts on improving retrieval and generation without requiring fine-tuned models.

## How to Use the Repository

### Embedding Model Evaluation
1. Open the provided Google Colab notebooks in 'Embedding_Model_Ev' Folder.
2. Select the CPU with High RAM.
3. Run the cells to evaluate embedding models across different datasets.
4. Modify the parameters to test different embedding models or datasets of your own.

### Advanced Prompt Engineering
1. Open the provided Google Colab notebooks in 'PromptEng_Ev' Folder. to run the advanced prompt-engineering experiments.
2. Select the T4-GPU with High RAM
3. Execute the notebook cells to design and evaluate different prompts for each dataset.
4. Compare the results of prompt-engineered RAG with state-of-the-art models.

## Datasets Used
- **TriviaQA** (open-domain question answering)
- **PubHealth** (domain-specific health information retrieval)
- **ARC-C** (AI2 Reasoning)
- - **MuSiQue** (multi-hop reasoning dataset)
 
