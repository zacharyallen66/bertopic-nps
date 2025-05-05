# bertopic-nps: BERTopic Survey Analysis

This project uses **BERTopic** and **OpenRouter LLMs** to extract and summarize insights from real-world customer survey feedback. The goal is to understand **Net Promoter Score (NPS)** transitions and the themes that drive customer satisfaction or dissatisfaction.

---

### 🧠 Key Features

- Topic modeling on open-ended survey responses using **BERTopic**
- Custom LLM summarization with **OpenRouter API**
- Segment-based comparison (e.g., Stayed Positive, Switched to Negative)
- Applied to business data to support executive NPS insights

---

### 📁 Files

| File | Description |
|------|-------------|
| `BertTopicSurveyData.ipynb` | Full analysis pipeline using BERTopic + OpenRouter |
| `BERTopic_Best_Practices.ipynb` | Walkthrough of BERTopic tuning, evaluation, and visualizations |

---

### 🖼️ Example Outputs

#### 🔍 Topic Map – Intertopic Distance
![Capture4](https://github.com/user-attachments/assets/cafa16a7-3fec-418e-aabd-59a79cb8ee5c)

#### 🌲 Topic Hierarchy – Clustering of Themes
![Capture3](https://github.com/user-attachments/assets/fde54ab7-21c2-43f3-bf63-056c770c5703)

#### 📊 Top-N Negative Topics
![Capture2](https://github.com/user-attachments/assets/a440cbdd-875c-45e9-a244-4dc4aedfd45a)

#### 📊 Top-N Positive Topics
![Capture1](https://github.com/user-attachments/assets/d7f41eaa-452b-4148-bea2-19a57f37df42)

#### 🧾 LLM-Generated Summaries by Segment
![Capture](https://github.com/user-attachments/assets/03ad7ffd-a59f-4a14-b680-11590d8a57bc)

---

### ⚙️ Technologies Used

- `Python` (pandas, numpy, matplotlib, plotly)
- `BERTopic`, `UMAP`, `HDBSCAN`
- `OpenRouter` API (LLM prompt-based summarization)
- Jupyter Notebooks for reproducibility

---

### 🚀 Run Locally

```bash
pip install -r requirements.txt
