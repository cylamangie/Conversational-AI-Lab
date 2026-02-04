# Conversational AI Lab – Week 3

## 📌 Overview
This project extends the exploration of conversational AI with **Ollama** and the **Qwen3 model**, focusing on dynamic system prompts, knowledge integration, and retrieval-augmented generation (RAG).  
It demonstrates how AI can provide accurate time updates, act as a university information assistant, and leverage embedded knowledge for precise answers.

> 📝 **Note**: This is the **third lab assignment** for **COM6104 – Topics in Data Science and Artificial Intelligence**.  
It documents hands-on experimentation with conversational design, prompt engineering, and retrieval-based AI.


## 🎯 Motivation
Modern AI systems must handle **real-time information**, **domain-specific knowledge**, and **retrieval-based queries**.  
This lab showcases practical techniques for:
- Updating system prompts dynamically (e.g., current time in Hong Kong).
- Embedding cached knowledge for efficient responses.
- Using RAG to answer academic queries with context-aware retrieval.


## ⚙️ Exercises Implemented
- **Exercise 1: Current Time Assistant**  
  AI updates system prompt with the exact current time in Hong Kong.  
  Demonstrates dynamic prompt engineering.

- **Exercise 2: HSU Knowledge Helper**  
  AI acts as a helper from Hang Seng University (HSU).  
  Uses cached Wikipedia data to answer questions about HSU history, leadership, and programs.  
  Replies are short and precise.

- **Exercise 3: Retrieval-Augmented Generation (RAG)**  
  AI integrates structured academic module data (course codes, names, lecturers).  
  Uses embeddings and vector search to retrieve relevant knowledge.  
  Answers student queries with context-aware precision.


## 📊 Sample Outputs

| Exercise   | Example Input | Example Output |
|------------|---------------|----------------|
| Current Time | "What time is it?" | *The current time is 11:52:48.* |
| HSU Helper | "When was HSU established?" | *HSU was established in 2010 as Hang Seng Management College and granted university status in 2018.* |
| RAG Query | "Who teaches COM6104?" | *The lecturer for COM6104 is Dr. WK Wong.* |


## 🚀 How to Run
```bash
pip install -r requirements.txt
python conversational_ai_week3.ipynb
```

## 📚 Course Context
Completed as part of **COM6104 – Topics in Data Science and Artificial Intelligence** at The Hang Seng University of Hong Kong.


## 💡 Reflection
This lab deepened my understanding of how conversational AI can be enhanced with **dynamic prompts**, **domain-specific knowledge bases**, and **retrieval-augmented generation**.  
It highlights the importance of combining prompt engineering with structured knowledge to deliver accurate, context-aware responses.


## 📚 Acknowledgements
Parts of this code were adapted from COM6104 lab materials provided by the instructor.  
This repository is licensed under the **MIT License**, which permits reuse and modification with proper attribution.
