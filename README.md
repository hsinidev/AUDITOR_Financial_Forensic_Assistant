<div align="center">
# 🚀 Auditor Financial Forensic Assistant
### *Modern, High-Performance Python Solution & Developer Suite*

<p align="center">
  [![Architect](https://img.shields.io/badge/Architect-Hsini%20Mohamed-0055ff?style=for-the-badge&logo=github&logoColor=white)](https://hsini.dev)
  [![Portfolio](https://img.shields.io/badge/Portfolio-hsini.dev-00c853?style=for-the-badge&logo=google-chrome&logoColor=white)](https://hsini.dev)
  [![Language](https://img.shields.io/badge/Language-Python-3776AB?style=for-the-badge)](https://github.com/hsinidev)
  [![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
</p>

</div>

---
## 🌟 Executive Overview

**Auditor Financial Forensic Assistant** is a production-grade **Python** platform engineered for high reliability, clean architectural separation, and frictionless developer workflow.

## ⚡ Key Highlights & Capabilities

- **Scalable Architecture**: Modular, decoupled components adhering to clean code principles.
- **Optimized Runtime**: Ultra-fast execution with minimal memory and CPU overhead.
- **Developer Tooling**: Standardized linting, formatting, and rapid local iteration setup.
- **Production Ready**: Built-in error resilience, validation, and structured logging.

---
## 🏗️ Architecture & Technology Stack

- **Primary Language**: `Python`
- **Design Pattern**: Modular Clean Architecture / Domain-Driven Design
- **License**: MIT Open Source Attribution

## 📖 Deep-Dive Technical Documentation

# AUDITOR - Financial Forensic & Tax Audit Assistant


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

**HSINI MOHAMED**  
*Enterprise Systems Architect & Financial AI Specialist*  

- **GitHub**: [@hsinidev](https://github.com/hsinidev)
- **LinkedIn**: [Moahmed Hsini](https://www.linkedin.com/in/moahmed-hsini-6059281a1/)
- **Email**: [hsini.moahmed@gmail.com](mailto:hsini.moahmed@gmail.com)
- **Website**: [hsini.dev](https://hsini.dev)

---
*Precision forensic financial analysis with offline data security.*

---
## 🚀 Quick Start & Installation

### 1. Clone the Repository
```bash
git clone https://github.com/hsinidev/AUDITOR_Financial_Forensic_Assistant.git
cd AUDITOR_Financial_Forensic_Assistant
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch the Application
```bash
python main.py
```


---

## 👨‍💻 System Architect & Author

<table align="center" style="border: none; background: transparent; width: 100%;">
  <tr>
    <td align="center" width="160" style="border: none; padding: 12px;">
      <img src="https://avatars.githubusercontent.com/u/232697467?v=4" width="120" height="120" style="border-radius: 50%; box-shadow: 0 8px 24px rgba(99,102,241,0.3); border: 2.5px solid #6366f1;" alt="Hsini Mohamed" />
      <br /><br />
      <b>Hsini Mohamed</b><br />
      <sub>Morocco 🇲🇦</sub>
    </td>
    <td style="border: none; padding: 12px; vertical-align: middle;">
      <h3 style="margin-top: 0;">🚀 System Architect & Full-Stack Engineer</h3>
      <p style="font-size: 0.95rem; line-height: 1.6; color: #475569;">
        Specializing in high-performance autonomous AI systems, deterministic multi-agent swarms, enterprise cloud architecture, and modern full-stack engineering.
      </p>
      <p>
        <a href="https://hsini.dev"><img src="https://img.shields.io/badge/Portfolio-hsini.dev-2563eb?style=flat-square&logo=google-chrome&logoColor=white" alt="Portfolio" /></a>
        <a href="mailto:contact@hsini.dev"><img src="https://img.shields.io/badge/Email-contact@hsini.dev-ea4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
        <a href="https://github.com/hsinidev"><img src="https://img.shields.io/badge/GitHub-@hsinidev-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
        <a href="https://linkedin.com/in/hsinidev/"><img src="https://img.shields.io/badge/LinkedIn-hsinidev-0077b5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
      </p>
    </td>
  </tr>
</table>

---

## 📄 License & Attribution

This project is distributed under the **MIT License**. See [`LICENSE`](LICENSE) for complete terms.

<div align="center">
  <sub>⚡ Designed, architected, and maintained with engineering precision by <b><a href="https://hsini.dev">Hsini Mohamed</a></b>.</sub>
</div>
