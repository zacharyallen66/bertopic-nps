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
![Capture1](https://github.com/user-attachments/assets/e2ca1fde-fcf6-437a-94b6-6248619f9196)

#### 📊 Top-N Negative Topics
![Capture2](https://github.com/user-attachments/assets/601eaecb-7d48-4046-8b67-2214cb8b44b9)

#### 📊 Top-N Positive Topics
![Capture3](https://github.com/user-attachments/assets/9bc9c394-f646-44eb-add0-52859811daed)

#### 🧾 LLM-Generated Summaries by Segment
![Capture4](https://github.com/user-attachments/assets/ca13de87-2f3c-43d0-a500-0e298c9fc89b)

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
