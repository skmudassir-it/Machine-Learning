# 🔍 Exploratory Data Analysis (EDA) — Credit Card Dataset

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A comprehensive **Exploratory Data Analysis (EDA)** on a credit card customer dataset using Python. This project demonstrates fundamental data science techniques including data inspection, statistical analysis, visualization, and insight generation.

---

## 📊 Dataset

- **Source:** [Bank Data Clustering — K-Means & PCA](https://github.com/CosmiX-6/Bank-data-clustering-KMean-Clustering-and-PCA)
- **Records:** 8,950 customers
- **Features:** 18 columns (credit limit, payments, balance, etc.)
- **Format:** CSV

---

## 📓 Notebook Contents

The notebook [`EdaPro.ipynb`](EdaPro.ipynb) covers:

| # | Section | Description |
|---|---------|-------------|
| 1 | Setup & Imports | pandas, matplotlib, seaborn, scipy |
| 2 | Data Loading | Read CSV from GitHub raw URL |
| 3 | First Look | `df.head()` and column inspection |
| 4 | Data Structure | `df.info()` — types, non-null counts |
| 5 | Statistical Summary | `df.describe().transpose()` |
| 6 | Correlation Analysis | Heatmap + top 5 strongest correlations |
| 7 | Missing Value Analysis | Null counts and percentages |
| 8 | Distribution Analysis | Histograms with mean/median markers |
| 9 | Outlier Detection | Box plots + IQR outlier counts |
| 10 | Skewness & Kurtosis | Distribution shape statistics |
| 11 | Pairwise Relationships | Pair plot (sampled if needed) |
| 12 | Key Insights & Next Steps | Summary of findings |

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas matplotlib seaborn numpy scipy jupyter
```

### Run the Notebook

```bash
git clone https://github.com/skmudassir-it/Machine-Learning.git
cd Machine-Learning
jupyter notebook EdaPro.ipynb
```

---

## 🛠️ Tech Stack

- **Python 3.x** — Core language
- **pandas** — Data manipulation
- **matplotlib** — Base plotting
- **seaborn** — Statistical visualizations
- **scipy** — Statistical functions (skew, kurtosis)
- **Jupyter Notebook** — Interactive computing environment

---

## 📈 Key Findings

- Correlation analysis reveals which features move together
- Distribution plots show skewness patterns across columns
- Box plots identify potential outliers for further investigation
- Pair plots visualize multi-dimensional relationships

> Full insights are embedded throughout the notebook with clear markdown explanations.

---

## 🔜 Next Steps

- Apply **clustering algorithms** (K-Means, DBSCAN) to segment customers
- Use **PCA** for dimensionality reduction
- Build **predictive models** for credit risk or spending behavior
- Handle outliers with capping or transformations

---

## 📁 Repository Structure

```
Machine-Learning/
├── EdaPro.ipynb      # Main EDA notebook (24 cells)
└── README.md         # This file
```

---

## 🤝 Contributing

This is a personal learning project, but suggestions are welcome! Feel free to open an issue or fork the repo.

---

## 📝 License

MIT — feel free to use and modify.

---

## 👤 Author

**Shaik Mudassir**

- GitHub: [@skmudassir-it](https://github.com/skmudassir-it)
- Email: skmudassir.it@gmail.com

---

⭐ **Star this repo** if you find it useful!
