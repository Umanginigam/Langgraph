# Agentic Workflow using LangGraph 

This project demonstrates an agentic task planner-reflector-executor loop using LangGraph. It breaks a user query into subtasks, solves them iteratively, and reflects on the results using a local LLM pipeline.

## 🚀 Features
- LangGraph-based agentic workflow
- Built-in planner, executor, and feedback loop
- Open-source and runs entirely in Colab
- No API key required (uses HuggingFace transformers)

## 📔 Notebook Preview
https://colab.research.google.com/drive/11RUUbC_VUY6AMJ6jsl-8g0oMaFwjv9Ck?usp=sharing

## 🧠 Architecture
User Query → PlanAgent → ToolAgent → Reflection → (loop) → Output

## 🔧 Requirements

Install dependencies:
```bash
pip install langgraph transformers matplotlib pandas
```
