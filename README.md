# AUDITOR - Financial Forensic & Tax Audit Assistant

![AUDITOR Banner](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge&logo=finance)
![Security](https://img.shields.io/badge/Security-Offline%20Financial%20Privacy-darkgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-orange?style=for-the-badge)

## 🎯 Project Overview
**AUDITOR** is an air-gapped, privacy-focused Retrieval-Augmented Generation (RAG) system created for forensic accountants, tax auditors, and corporate financial controllers. It processes general ledgers, transaction logs, corporate invoices, and tax regulatory codes locally—flagging accounting anomalies and compliance risks while keeping private financial records 100% offline.

---

## ✨ Key Features
- 🚩 **Ledger Risk Flagging**: Cross-references transaction ledgers against local tax laws, GAAP/IFRS standards, and compliance rules.
- 🔎 **Forensic Pattern Search**: Performs hybrid semantic and numeric text queries across thousands of financial statements and audit trails.
- 📋 **Automated Audit Dossiers**: Generates comprehensive local audit summary reports ready for board reviews or regulatory compliance audits.
- 🔒 **Zero Data Leakage**: Protects sensitive financial disclosures, payroll records, and proprietary ledger logs from cloud leaks.
- 📊 **Invoice & Receipt Parsing**: Extracts tabular numerical data from PDF invoices and bank statements seamlessly.

---

## 🛠 System Architecture & Stack
- **Interface**: Custom Streamlit Financial Dashboard (`app.py`)
- **RAG Engine**: Forensic query retrieval system (`rag_engine.py`) using ChromaDB vector storage
- **Data Ingestion**: Multi-format financial document loader for CSV, Excel, PDF ledgers (`ingest.py`)
- **LLM Engine**: Local Ollama execution (Llama 3 / Qwen 2.5 / Gemma 2)

---

## 🚀 Quick Start Guide

### Prerequisites
- Python 3.10+
- [Ollama](https://ollama.ai/) installed locally

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/hsinidev/AUDITOR_Financial_Forensic_Assistant.git
   cd AUDITOR_Financial_Forensic_Assistant
   ```
2. Activate a Python virtual environment:
   ```bash
   python -m venv venv
   # Windows:
   venv\Scripts\activate
   # Linux/macOS:
   source venv/bin/activate
   ```
3. Install dependencies:
   ```bash
   pip install streamlit chromadb langchain ollama pandas pypdf openpyxl
   ```

### Usage
1. Place financial ledgers, tax codes, and audit records into the local data directory.
2. Ingest ledger data into the vector database:
   ```bash
   python ingest.py
   ```
3. Launch the financial audit interface:
   ```bash
   streamlit run app.py
   ```

---

## 📂 Project Structure
```
AUDITOR_Financial_Forensic_Assistant/
├── app.py           # Financial audit interface & query dashboard
├── ingest.py        # Financial ledger & tax document processing script
├── rag_engine.py    # Forensic retrieval engine & anomaly detection pipeline
├── prompt.json      # Forensic accounting prompts & audit scoring rules
├── system.txt       # System role definition & security compliance spec
├── skills.md        # Specialized forensic accounting tool definitions
└── README.md        # Project documentation
```

---

## 👤 Author & Maintainer
**HSINI MOHAMED**  
*Enterprise Systems Architect & Financial AI Specialist*  

- **GitHub**: [@hsinidev](https://github.com/hsinidev)
- **LinkedIn**: [Moahmed Hsini](https://www.linkedin.com/in/moahmed-hsini-6059281a1/)
- **Email**: [hsini.moahmed@gmail.com](mailto:hsini.moahmed@gmail.com)
- **Website**: [hsini.dev](https://hsini.dev)

---
*Precision forensic financial analysis with offline data security.*
