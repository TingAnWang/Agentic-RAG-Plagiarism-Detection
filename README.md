# Agentic-RAG-Plagiarism-Detection  
A Multi-LLM Collaboration Approach for Reliable Plagiarism Detection and Knowledge Gap Identification

## Overview

This repository contains two implementations of an **Agentic Retrieval-Augmented Generation (RAG) system** for **plagiarism detection and knowledge validation** using **multi-LLM collaboration**. The methods are inspired by the paper:  
🚀 ["Don't Hallucinate, Abstain: Identifying LLM Knowledge Gaps via Multi-LLM Collaboration"](https://arxiv.org/abs/2402.00367) 🚀  

Two approaches are implemented:

- **COOPERATE Mode** 🏗️ – Multiple LLMs act as experts, providing critiques before a final judge model makes a decision.
- **COMPETE Mode** ⚔️ – Alternative LLMs generate conflicting answers, and the main LLM's response stability determines if it abstains.

Both modes enhance **plagiarism detection, fact verification, and knowledge reliability assessment**.

---

## Features

✅ **FAISS for document retrieval**: Efficient similarity search for identifying relevant documents.  
✅ **CrossEncoder for reranking**: Improves retrieval quality by scoring document relevance.  
✅ **Multi-LLM Collaboration**: Different models interact dynamically to refine answers.  
✅ **Memory-Efficient Execution**: Models are loaded on demand, optimizing GPU usage.  
✅ **Plagiarism Detection**: Highlights text overlap and semantic similarity between user input and sources.  
✅ **RAG-Enhanced Generation**: LLMs operate with retrieved knowledge to improve answer reliability.  

---

## 🚀 Run on Google Colab

You can try out this project directly in **Google Colab**.  

👉 Click below to open:  

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1-9hZ8g48xPeyQ8BbZJqGRh5W5voBQBb_?usp=sharing)

