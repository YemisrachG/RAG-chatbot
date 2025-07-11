# 🧠 Intelligent Complaint Analysis for Financial Services

A Retrieval-Augmented Generation (RAG)-powered chatbot that helps internal teams at **CrediTrust Financial** transform raw customer complaints into real-time, actionable insights.

---

## 🚀 Project Objectives

- Reduce the time it takes to identify major complaint trends from **days to minutes**
- Enable **non-technical teams** (Product, Support, Compliance) to access insights without a data analyst
- Transition the company from **reactive** to **proactive** issue management

---

## 🏗️ System Architecture

```text
[ Complaint Dataset (CFPB) ]
         ↓
[ Preprocessing + Cleaning ]
         ↓
[ Text Chunking + Embedding ]
         ↓
[ Vector Store (FAISS) ]
         ↓        ↘
[ RAG Pipeline ]   [ User Question ]
         ↓
[ GPT-4 / LLM Output ]
         ↓
[ Streamlit Chat Interface 

🛠️ Technologies Used
•	Python, Streamlit
•	LangChain, FAISS
•	Sentence-Transformers (all-MiniLM-L6-v2)
•	OpenAI GPT-4 API
•	CFPB Complaint Dataset
