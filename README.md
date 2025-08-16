# 🔍 Search Queries Analysis & Anomaly Detection  

## 📌 Project Overview  
This project analyzes **search query performance data** (from Google Search Console or similar datasets) to uncover insights such as:  
- Most common words in search queries  
- Top queries by **Clicks** and **Impressions**  
- Detection of anomalies in query performance using **Isolation Forest**  

The analysis is visualized using **Plotly** for interactive charts.  

---

## 📂 Dataset  
The project expects a CSV file named **`Queries.csv`** with the following columns:  

| Column        | Description |
|---------------|-------------|
| Top queries   | The search query text |
| Clicks        | Number of clicks |
| Impressions   | Number of times shown |
| CTR           | Click-through rate (e.g., `12.3%`) |
| Position      | Average ranking position |

---

## ⚙️ Features Implemented  
✅ Data Cleaning (CTR & Position conversion to numeric)  
✅ Text Analysis – Most frequent words in queries  
✅ Performance Analysis – Top queries by clicks & impressions  
✅ Anomaly Detection – Using **Isolation Forest**  

---

## 📊 Visualizations  
- 📌 **Word Frequency Chart** – Top 20 most common words  
- 📌 **Top Queries by Clicks** – Bar chart  
- 📌 **Top Queries by Impressions** – Bar chart  

---

## 🛠️ Technologies Used  
- **Python**  
- **Pandas** – Data manipulation  
- **Plotly Express** – Interactive charts  
- **Scikit-learn** – Isolation Forest anomaly detection  

---

## 🚀 How to Run  

### 1. Clone the repo  
```bash
git clone https://github.com/your-username/search-queries-analysis.git
cd search-queries-analysis
