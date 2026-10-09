# Multi-Agent Procurement Exception Copilot 🤖💼

An AI-powered Procurement Exception Copilot built with **LangGraph**, **LangChain**, **Streamlit**, and **RAG** for automated invoice data extraction, policy compliance auditing, and human-in-the-loop exception resolution.

## 🌟 Key Features
- 📄 **Invoice Data Extraction:** Parses raw invoice text/emails into structured JSON formats.
- ⚖️ **RAG Policy Audit Engine:** Evaluates invoices against procurement compliance guidelines (e.g., PO spending limits, tax ID requirements).
- 🚨 **Risk & Compliance Flags:** Automatically detects policy violations (e.g., `POL_TAX_02`, `POL_VAR_01`) and assigns risk scores.
- ✉️ **Human-in-the-Loop Operator Dashboard:** Interactive Streamlit dashboard generating draft resolution emails to vendors with manual approval/override controls.

## 🛠️ Tech Stack
- **Dashboard:** Streamlit
- **Agent Framework:** LangGraph / LangChain
- **Vector Database:** ChromaDB
- **LLM Provider:** Groq
- **Language:** Python
