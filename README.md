# LangChain Prompt LLM Chain

A simple beginner-friendly project demonstrating how to build an **LLM chain using LangChain and Google Gemini**.

This project shows how to:
- Load environment variables securely using `python-dotenv`
- Connect LangChain with Google Gemini
- Create prompts using `ChatPromptTemplate`
- Send prompts to an LLM
- Parse the LLM response using `StrOutputParser`
- Build a simple LangChain pipeline using the `|` operator

---

## 📌 Project Overview

The project demonstrates the basic flow of a LangChain application:

User Input  
↓  
Prompt Template  
↓  
Google Gemini LLM  
↓  
Output Parser  
↓  
Final Response

The main purpose of this project is to understand the fundamentals of **Prompt Templates, LLMs, Chains, and Output Parsers in LangChain**.

---

## 🛠️ Technologies Used

- Python
- LangChain
- Google Gemini
- `langchain-google-genai`
- `python-dotenv`

---

## 📂 Project Structure

```text
langchain-prompt-llm-chain/
│
├── langchain-prompt-llm-chain.ipynb
├── requirements.txt
├── .env
└── README.md
