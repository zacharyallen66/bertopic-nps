# bertopic-nps# BERTopic Survey Analysis

This project uses **BERTopic** and **OpenRouter LLMs** to extract and summarize insights from real-world customer survey feedback. The goal is to understand **Net Promoter Score (NPS) transitions** and the themes that drive customer satisfaction or dissatisfaction.

---

## 🧠 Key Features

- Topic modeling on open-ended survey responses using **BERTopic**
- Custom prompt-based LLM summarization using **OpenRouter API**
- Comparison of segments (e.g. Stayed Positive, Switched to Negative)
- Applied to business data to support NPS movement analysis

---

## 📁 Files

| File | Description |
|------|-------------|
| `BertTopicSurveyData.ipynb` | Full analysis pipeline using BERTopic + OpenRouter |
| `BERTopic_Best_Practices.ipynb` | Walkthrough of BERTopic tuning, evaluation, and visualization methods |

---

## ⚙️ Technologies Used

- Python (pandas, sklearn, umap-learn, BERTopic)
- OpenRouter API for LLM-based summarization
- Matplotlib & plotly for visualization
- Survey feedback data from real client NPS responses

---

## 🚀 Run Locally

```bash
pip install -r requirements.txt
