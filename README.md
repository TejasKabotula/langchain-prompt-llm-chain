# LangChain Prompt LLM Chain

A simple beginner-friendly project demonstrating how to build an **LLM chain using LangChain and Google Gemini**.

The project takes text input from the user, passes it through a prompt template, sends it to the Gemini LLM, and returns the generated summary.

---

## 🚀 Project Overview

This project demonstrates a basic **LangChain Expression Language (LCEL)** pipeline.

The workflow is:

```text
User Input
    ↓
ChatPromptTemplate
    ↓
Google Gemini LLM
    ↓
StrOutputParser
    ↓
AI Response
```

The main goal of this project is to understand how prompts, LLMs, output parsers, and chains work together in LangChain.

---

## 🛠️ Technologies Used

- Python
- LangChain
- Google Gemini
- python-dotenv

### LangChain Components

- `ChatGoogleGenerativeAI`
- `ChatPromptTemplate`
- `StrOutputParser`

---

## 📂 Project Structure

```text
langchain-prompt-llm-chain/
│
├── langchain-prompt-llm-chain.ipynb
├── requirements.txt
├── .env.example
└── README.md
```

---

## 🔑 Environment Setup

This project requires a **Google Gemini API key**.

### 1. Create a `.env` file

Use the provided `.env.example` file as a template.

`.env.example`:

```env
GOOGLE_API_KEY=your_google_api_key_here
```

Create your own `.env` file:

```env
GOOGLE_API_KEY=your_actual_api_key
```

The project loads the API key using `python-dotenv`:

```python
from dotenv import load_dotenv

load_dotenv()
```

---
## 📋 Requirements

The project dependencies are listed in `requirements.txt`:

```text
python-dotenv
langchain-google-genai
langchain-core
```

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## 🧠 Concepts Learned

This project covers:

- Environment variables
- API key management
- Google Gemini integration
- LangChain basics
- Prompt templates
- Dynamic prompt variables
- LLM chains
- Output parsers
- LangChain Expression Language (LCEL)
- Pipe operator (`|`)
- `.invoke()` method

---


## 👨‍💻 Author

**Tejas Kabotula**

GitHub: [TejasKabotula](https://github.com/TejasKabotula)

---

## ⭐ Support

If you found this project useful, consider giving the repository a ⭐ on GitHub.
