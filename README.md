# MAIS-Multi-Agent-Investment-System

## 🎯 Overview

MAIS is an intelligent multi-agent system for analyzing and recommending investment opportunities based on multiple criteria: profitability, risk, sustainability, and ethical compliance.

## 🤖 Architecture

The system relies on specialized autonomous agents:
- **Analyst Agent**: Financial data extraction and analysis
- **Risk Agent**: Volatility assessment and ESG indicators evaluation
- **Strategic Agent**: Comparison based on investor objectives
- **Decision Agent**: Consolidation and justified final decision

## Structure du repo :
```
genetic-ai-investment-prototype/
├── data/
│   ├── raw/
│   └── processed/
│
├── rag_data/                 # PDFs, rapports, news
│
├── agents/
│   ├── __init__.py
│   ├── analyst_agent.py      # Récupère et résume données
│   ├── risk_agent.py         # Calcule risques (Sharpe, volatilité, ESG)
│   ├── strategy_agent.py     # Applique MCDA selon profil investisseur
│   └── decision_agent.py     # Agrège + génère recommandation (LLM)
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_test_agents_locally.ipynb   # Pour tester chaque agent
│   └── 03_full_simulation.ipynb       # Boucle multi-agents + consensus
│
├── app.py                    # Streamlit
├── requirements.txt
└── README.md

```

## 🛠️ Tech Stack # coming soon

- **Agent Framework**: CrewAI / LangGraph
- **Financial Data**: yfinance, Alpha Vantage
- **LLM & RAG**: GPT-4, LlamaIndex, FAISS
- **Analysis**: Pandas, NumPy, Scikit-learn
- **Interface**: Streamlit
- **XAI**: SHAP, LIME

## 🚀 Installation
```bash
# Coming soon
```

## 📊 Usage
```bash
# Coming soon
```

## 📝 Project Status

🚧 Under active development
