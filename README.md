# AI_AGENTS_USING_LangGraph
# Conditional_Workflow

---

# 🚀 AI-Powered Customer Review Analysis using LangGraph

This project implements an **end-to-end AI workflow** that takes a customer review as input and processes it automatically using a **graph-based conditional workflow**.

The system intelligently routes reviews based on **sentiment** and generates appropriate, context-aware responses.

---

## 🔄 Workflow Overview

1. **Input:** Customer review text
2. **Sentiment Analysis:** Classifies the review as **Positive** or **Negative**

### ✅ If the Review is Positive

* Generates a **warm and appreciative response**

### ❌ If the Review is Negative

* Detects the **issue type** (Bug, UX, Performance, Support, etc.)
* Identifies the **tone** (Angry, Frustrated, Calm, etc.)
* Determines the **urgency level**
* Generates a **polite, empathetic customer support response**

All decisions and transitions are handled automatically using a **LangGraph-based workflow**.

---

## 🧠 Key Features

* Conditional routing based on sentiment
* Graph-based workflow orchestration with **LangGraph**
* Structured LLM outputs using **Pydantic**
* Fast inference using **Groq LLM (LLaMA 3.1)**
* Clean and modular workflow design

---

## 🛠 Tech Stack

* **Python**
* **LangGraph**
* **LangChain**
* **Groq LLM (LLaMA 3.1)**
* **Pydantic**
* **dotenv**

---

## 📌 Use Cases

* Customer review analysis
* Customer support automation
* Feedback-driven decision systems
* AI-powered workflow orchestration

---

## ▶️ How It Works

* A review is passed as input to the workflow
* The graph evaluates sentiment
* The workflow routes execution based on conditions
* The final response is generated automatically

---



