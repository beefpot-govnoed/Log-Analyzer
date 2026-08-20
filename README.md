# 🔒 Log-Analyzer

**AI-Powered Log Analyzer for Cybersecurity Threat Detection**

*Transforming raw logs into actionable security intelligence*

---

## ✨ Features

- 🎯 **Smart Detection** — Auto-detects log formats and identifies security event types (DDOS, XSS, SQL Injection, etc.)
- 🤖 **AI-Powered Analysis** — Uses CyberSecQwen-4B for expert analysis and groups similar threats automatically
- 📊 **Visual Reports** — Severity distribution charts, security event type statistics, n-gram pattern analysis
- 🚀 **High Performance** — Batch processing for large logs, optimized n-gram analysis, GPU acceleration support

---

## 🚀 Quick Start

### Prerequisites

- Google Colab (recommended) or local Python 3.8+
- GPU T4 or better (for optimal performance)
- Internet connection for model download

### Installation

```bash
git clone https://github.com/beefpot-govnoed/Log-Analyzer.git
cd CyberLogAI
```

### Usage in Google Colab

1. Open `main.ipynb` in Google Colab
2. Select **Runtime → Change runtime type → GPU T4**
3. Run all cells
4. Upload your `.log` file when prompted
5. Get AI-powered analysis

---

## 🎯 Supported Security Events

| Event Type | Description |
|------------|-------------|
| 🌊 **DDOS** | Distributed Denial of Service |
| 💉 **XSS** | Cross-Site Scripting |
| 📈 **SCALE_INJECTION** | Resource scaling attack |
| 🤖 **TG** | Threat Group activity |
| 🔍 **SQL Injection** | Database injection |

---

## 📁 Project Structure

```
Log-Analyzer/
├── main.ipynb    # Main notebook
├── main.py     # Python script version
├── requirements.txt    # Dependencies
└── README.md           # Documentation
```

---

## 🔧 Configuration

| Parameter | Default | Description |
|-----------|---------|-------------|
| `MAX_LOGS_FOR_ANALYSIS` | 10000 | Maximum logs to process |
| `MAX_GROUPS_TO_ANALYZE` | 5 | Groups for LLM analysis |
| `EMBEDDING_BATCH_SIZE` | 32 | Batch size for embeddings |

---

## 🛠️ Tech Stack

- Python 3.8+
- PyTorch 2.0+
- Transformers (Hugging Face)
- CyberSecQwen-4B (AI model)
- Sentence-Transformers (clustering)
- scikit-learn (DBSCAN)
- Matplotlib (visualization)

---

## ⚠️ Disclaimer

This tool is for **educational and defensive purposes only**. Use responsibly and only on systems you own or have permission to test.
