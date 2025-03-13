# Sexism Detection


## About the Project

This project, developed for the NLP course at the **University of Bologna (UniBo)**, focuses on identifying sexist language in tweets. It employs various NLP techniques, including **LSTM models, Transformers, and Large Language Models (LLMs)**, to improve sexism classification.

---

## Project Breakdown

The work is divided into two key tasks:

- **Task 1**: Implementing LSTM and Transformer models to classify sexist content.
- **Task 2**: Leveraging Large Language Models (LLMs) for sexism detection through **zero-shot** and **few-shot learning**.

---

## Datasets Used

- 📌 **EXIST dataset** (Github) – Used in Task 1.
- 📌 **EDOS test set** (Github)) – Used in Task 2.

---

## Approaches and Models

### Task 1: LSTM & Transformer-Based Models

#### **LSTM-Based Models**
Three variations of **LSTM architectures** were explored:

📌 **Baseline Model**: A **BiLSTM** followed by a fully connected layer.  
📌 **Model 1**: A deeper LSTM version with an **extra LSTM layer**.  


#### **Transformer-Based Model**
A fine-tuned **Twitter-roBERTa-base model** (from Hugging Face) was used to detect sexist speech, building on pre-trained language understanding capabilities.

---

### Task 2: LLM-Based Models

For this task, **zero-shot and few-shot learning** techniques were tested using **LLMs**:

📌 **Meta-Llama-3.1-8B-Instruct**  
📌 **Phi-3-mini-4k-instruct**  

These models were evaluated for their effectiveness in sexism detection without requiring extensive fine-tuning.

---

## 📌 Summary

This project integrates both **traditional deep learning models (LSTMs)** and **cutting-edge language models (Transformers & LLMs)** to classify sexist content in text. The **comparative analysis** between these approaches helps to understand the effectiveness of each technique in real-world applications.

