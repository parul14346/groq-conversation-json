# groq-conversation-json
This project implements two tasks using the Groq API: (1) Conversation management with summarization, supporting truncation by messages or length and periodic k-turn summaries; (2) JSON schema extraction from chats, capturing structured fields like name, email, phone, location, and age.

# Groq API Assignment 🚀

## 📌 Overview
This project demonstrates the use of **Groq API (OpenAI SDK compatible)** to build two core tasks:

1. **Conversation History with Summarization**  
   - Maintains a running user–assistant chat history.  
   - Supports truncation by number of messages and character length.  
   - Automatically summarizes the conversation after every *k* turns.  
   - Keeps long chats concise while preserving key information.  

2. **JSON Schema Classification & Extraction**  
   - Defines a JSON schema to extract structured user details (name, email, phone, location, age).  
   - Uses Groq function calling for structured output.  
   - Demonstrated with at least 3 chat samples and validated JSON results.  

---

## ⚙️ Tech Stack
- **Python** (Google Colab)  
- **Groq API** (OpenAI-compatible SDK)  

---

## 🚀 How to Run
1. Clone the repo:  
   ```bash
   git clone https://github.com/your-username/groq-chat-extraction.git
