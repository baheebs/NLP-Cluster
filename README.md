# 🧠 NLP Cluster

This project performs **text clustering** on the **ABC News Headlines dataset** using **TF-IDF** and **KMeans**.  
It also generates **word clouds** to visualize frequent terms in each cluster.

---

## 📂 Dataset
The dataset used is [`abcnews-date-text.csv`](abcnews-date-text.csv), which contains Australian Broadcasting Corporation (ABC) news headlines.

**Columns:**
- `publish_date` — Date of publication (YYYYMMDD)
- `headline_text` — News headline text

---

## ⚙️ Features
- Text preprocessing (tokenization, stopword removal, lemmatization)
- TF-IDF vectorization of headlines
- K-Means clustering for topic grouping
- WordCloud visualization for each cluster

---

## 🚀 How to Run (Google Colab or Local Jupyter)
1. Clone this repository:
   ```bash
   git clone https://github.com/baheej/nlp-cluster.git
   cd nlp-cluster
