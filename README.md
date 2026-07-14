# DevelopersHub Corporation — AI/ML Engineering Internship

**Intern Name:** Muhammad Arslan Saeed  
**Due Date:** 21st July, 2026

## Tasks Completed

### Task 1: News Topic Classifier Using BERT
- **Objective:** Classify news headlines into topic categories using transformers
- **Model:** facebook/bart-large-mnli (Zero-Shot Classification)
- **Approach:** Pre-trained transformer with zero-shot learning — no fine-tuning required
- **Categories:** Business, Sports, Technology, Health, Entertainment, Politics
- **Dataset:** 8 sample news headlines
- **Key Finding:** Zero-shot classification effectively categorizes news without task-specific training

### Task 4: Context-Aware Chatbot Using RAG
- **Objective:** Build conversational chatbot with retrieval and context memory
- **Approach:** Simple RAG using TF-IDF + Cosine Similarity
- **Components:** Document retriever, context memory, response generator
- **Knowledge Base:** 12 documents about DevelopersHub internship
- **Features:** Top-2 document retrieval, conversation history, context-aware responses
- **Key Finding:** RAG approach enables accurate responses without LLM API dependency

## How to Run
1. Install requirements: `pip install pandas numpy matplotlib seaborn scikit-learn transformers`
2. Open `.ipynb` files in Jupyter Notebook or VS Code
3. Run all cells top to bottom

## Repository Structure
