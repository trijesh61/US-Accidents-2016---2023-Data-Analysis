# 🚗 US Accidents (2016–2023) - Data Analysis

This repository contains my exploratory data analysis (EDA) of the **US Accidents (2016–2023)** dataset. The dataset spans 7.7 million traffic incidents across 49 US states, collected through multiple real-time traffic APIs from February 2016 to March 2023.

---

## 📌 Project Description

The goal of this project is to uncover trends, patterns, and insights from historical accident data in the US. This analysis focuses on:

- Accident severity distribution
- Temporal and spatial patterns
- Environmental impact on accidents
- Identifying accident hotspots

---

## 📁 Dataset Source

- **Kaggle**: [US Accidents (2016 - 2023)](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)
- **Size**: ~7.7 million records
- **Coverage**: 49 US states

---

## 🔧 Tools Used

- **Language**: Python
- **Libraries**:
  - Pandas & NumPy – Data handling
  - Matplotlib & Seaborn – Visualization


---

## 🧪 Analysis Workflow

1. **Data Loading & Setup**
   - Read CSV using pandas
   - Basic understanding of the data shape and columns

2. **Missing Value Handling**
   - Used `missingno` to visualize null values
   - Dropped or filled columns as necessary

3. **Exploratory Data Analysis (EDA)**
   - Top cities and states by accident count
   - Hourly and weekly accident trends
   - Severity-wise accident distribution
   - Impact of visibility, temperature, humidity, etc.

4. **Visualization Highlights**
   - Count plots, histograms, line graphs

---

## 📊 Key Insights

- **California** has the highest number of recorded accidents.
- Most accidents occur during **morning and evening rush hours**.
- **Severity 2** accidents are the most frequent.
- Bad weather (e.g., fog, rain) correlates with higher severity.
- **Urban areas** report significantly more incidents.

---

## 📂 Files

```
📦 US-Accidents-2016---2023-Data-Analysis
 ┣ 📄 US_Accidents.ipynb         → Main notebook with full EDA
 ┗ 📄 README.md                  → Project documentation
```

---

## 📚 Citation

If you use this dataset, please cite:

- Moosavi, Sobhan, et al. “A Countrywide Traffic Accident Dataset.” 2019.
- Moosavi, Sobhan, et al. "Accident Risk Prediction based on Heterogeneous Sparse Data." ACM SIGSPATIAL, 2019.

---

## 🛡️ License

This project is under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License**. Use only for academic and research purposes.

---

## 🤝 Connect with Me

- **LinkedIn**: [Trijesh Kondapuram](https://www.linkedin.com/in/trijesh-kondapuram/)
- Feel free to ⭐ the repo if you find this work useful!
