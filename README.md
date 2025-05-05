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
![Intertopic Distance Map]![Capture](https://github.com/user-attachments/assets/2e691670-ad20-49ad-b686-b807f37279f7)

#### 🌲 Topic Hierarchy – Clustering of Themes
![Hierarchical Clustering]![Capture1](https://github.com/user-attachments/assets/e2ca1fde-fcf6-437a-94b6-6248619f9196)

#### 📊 Top-N Negative Topics
![Negative Topics](images/Capture2.PNG)

#### 📊 Top-N Positive Topics
![Positive Topics](images/Capture3.PNG)

#### 🧾 LLM-Generated Summaries by Segment
![Summarized Insights](images/Capture4.PNG)

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
