# 🧠 NLP Cluster

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/baheebs/NLP-Cluster/blob/main/nlp_cluster.ipynb)

This project performs **text clustering** on the **ABC News Headlines dataset** using **TF-IDF**, **KMeans**, and **WordCloud** visualizations.  
It helps discover common topics and patterns in large collections of news headlines.

---

## 📊 Dataset

The dataset used is [`abcnews-date-text.csv`](abcnews-date-text.csv), which contains over one million headlines published by the **Australian Broadcasting Corporation (ABC)**.

| Column | Description |
|:--------|:-------------|
| `publish_date` | Date of publication (YYYYMMDD) |
| `headline_text` | The headline text |

> In this project, a sample of 10,000 headlines was used for clustering.

---

## ⚙️ Features

- 🔤 **Text Preprocessing:** tokenization, stopword removal, lemmatization  
- 📈 **TF-IDF Vectorization:** converts text into numerical form  
- 🎯 **KMeans Clustering:** groups similar headlines  
- ☁️ **WordClouds:** visual representation of frequent words per cluster  

---

## 🚀 How to Run

### 🔹 Option 1 — Run in Google Colab
Click the **“Open in Colab”** button above or open the notebook directly:
```text
https://colab.research.google.com/github/baheebs/NLP-Cluster/blob/main/nlp_cluster.ipynb


🔹 Option 2 — Run Locally (Mac / Windows)

Clone the repository

git clone https://github.com/baheebs/NLP-Cluster.git
cd NLP-Cluster


Create a virtual environment (recommended)

python3 -m venv venv
source venv/bin/activate     # on macOS/Linux
# OR
venv\Scripts\activate        # on Windows


Install dependencies

pip install -r requirements.txt


Run the notebook

jupyter notebook nlp_cluster.ipynb