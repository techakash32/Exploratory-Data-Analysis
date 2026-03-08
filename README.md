# 📊 Exploratory Data Analysis (EDA) Practice

> A personal repository where I practice and document **Exploratory Data Analysis** techniques on real-world datasets using Python.

---

## 🧭 What is EDA?

Exploratory Data Analysis is the process of **understanding a dataset before modeling** — finding patterns, spotting anomalies, checking assumptions, and summarizing main characteristics using statistics and visualizations.

---

## 🗂️ Repository Structure

```
exploratory-data-analysis/
│
├── datasets/                  # Raw CSV / Excel datasets
│
├── notebooks/                 # Jupyter notebooks per dataset
│   ├── 01_dataset_name.ipynb
│   ├── 02_dataset_name.ipynb
│   └── ...
│
├── outputs/                   # Saved plots and charts
│
├── requirements.txt           # Python dependencies
└── README.md
```

---

## 🔍 EDA Checklist (What I Practice)

Each notebook typically covers:

- **Data Loading** — import CSV / Excel / database
- **Shape & Size** — rows, columns, memory usage
- **Data Types** — numeric, categorical, datetime
- **Missing Values** — null counts, heatmaps, handling strategies
- **Descriptive Statistics** — mean, median, std, min/max, quartiles
- **Duplicate Detection** — finding and dropping duplicates
- **Univariate Analysis** — histograms, boxplots, value counts
- **Bivariate Analysis** — scatter plots, correlation matrix, heatmaps
- **Outlier Detection** — IQR method, Z-score, boxplots
- **Feature Distributions** — skewness, kurtosis
- **Encoding & Cleanup** — label encoding, dtype corrections
- **Insights & Observations** — key takeaways from each dataset

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.x | Core language |
| Pandas | Data loading & manipulation |
| NumPy | Numerical operations |
| Matplotlib | Basic plotting |
| Seaborn | Statistical visualizations |
| Plotly | Interactive charts |
| Jupyter Notebook | Interactive analysis environment |

---

## ⚙️ Setup

### 1. Clone the repository
```bash
git clone https://github.com/your-username/exploratory-data-analysis.git
cd exploratory-data-analysis
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter
```bash
jupyter notebook
```

---

## 📦 requirements.txt

```
pandas
numpy
matplotlib
seaborn
plotly
jupyter
scikit-learn
```

---

## 📈 Datasets Analyzed

| # | Dataset | Source | Key Techniques |
|---|---------|--------|----------------|
| 1 | *(Add your dataset)* | Kaggle / UCI | *(e.g. missing values, correlation)* |
| 2 | *(Add your dataset)* | Kaggle / UCI | *(e.g. outlier detection, encoding)* |

> More datasets will be added as I continue practicing.

---

## 💡 Key Learnings

- How to identify and handle **missing data** effectively
- Difference between **univariate** and **bivariate** analysis
- How **correlation** does not imply causation
- Importance of **visualizing distributions** before choosing a model
- How **outliers** can skew statistical measures

---

## 🔮 What's Next

- [ ] Add more real-world datasets (healthcare, finance, sports)
- [ ] Practice feature engineering after EDA
- [ ] Add automated EDA using `ydata-profiling` (formerly `pandas-profiling`)
- [ ] Connect EDA findings to ML model building

---

## 📄 License

This repository is for **personal learning and practice**.  
Feel free to fork it and use it for your own EDA journey!

---

## 🙋‍♂️ Author

**Your Name**  
Practicing data analysis one dataset at a time. 📉📈  
[GitHub](https://github.com/your-username) · [LinkedIn](https://linkedin.com/in/your-profile)
