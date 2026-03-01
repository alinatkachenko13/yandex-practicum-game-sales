# 🎮 Video Game Sales Analysis

> End-to-end EDA and statistical analysis to plan a 2017 ad campaign for the online store “Streamchik”

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)

---

## ✨ Why this project stands out

- **Real business goal:** choose platforms/genres for a 2017 marketing strategy
- **Full analytics pipeline:** data cleaning → EDA → hypothesis testing → recommendations
- **Strong foundations for ML:** solid preprocessing, feature engineering, and statistical rigor

---

## 📋 Project Overview

This project analyzes historical game sales (~17K records) to identify market patterns and inform budget allocation for North America (NA), Europe (EU), and Japan (JP). The notebook includes:

- **Data preparation**: type conversion, missing values strategy, duplicates, total sales feature
- **Exploratory analysis**: trends over time, platform lifecycle, genre distribution, regional preferences
- **Statistical testing**: t-tests for key business hypotheses with α control
- **Actionable insights**: platform/genre focus and campaign guidance by region

---

## 🧰 Tech Stack

| Category          | Tools               |
|-------------------|---------------------|
| **Language**      | Python 3            |
| **Data**          | pandas              |
| **Visualization** | matplotlib, seaborn |
| **Statistics**    | scipy.stats         |
| **Environment**   | Jupyter Notebook    |

---

## 🧠 Skills Demonstrated

- **Data preprocessing:** imputation by groups, type fixes, handling “tbd”, deduplication
- **EDA & visualization:** distributions, correlations, time dynamics, segmentation
- **Statistical inference:** hypothesis testing, significance levels, interpretation
- **Business framing:** turning analysis into concrete, region-aware recommendations

---

## 🚀 Getting Started

### Install dependencies

```bash
pip install -r requirements.txt
```

### Data availability

The dataset used in this project is not included in the repository due to access restrictions. The notebook contains all analysis logic and results, but running it locally requires the original `games.csv`.

If you have access to the dataset, place it in `datasets/` or update the path in the notebook:

```python
# Default (Practicum environment)
data = pd.read_csv('/datasets/games.csv')

# Local run
data = pd.read_csv('datasets/games.csv')
```

### Review the analysis

You can open the notebook to review the full analysis, visualizations, and conclusions:

```bash
jupyter notebook game_sales_analysis.ipynb
```

---

## 📁 Project Structure

```
yandex-practicum-game-sales/
├── game_sales_analysis.ipynb   # Main analysis notebook
├── main.py                     # Project stub
├── requirements.txt            # Dependencies
├── README.md                   # Documentation
└── datasets/                   # Data directory
    └── games.csv               # Game sales dataset
```

---

## 📊 Key Findings (from the analysis)

- **Relevant period:** 2006–2016 (platform lifecycle ~6 years)
- **Promising platforms for 2017:** PS4, Xbox One, WiiU, PSV, 3DS
- **Top genres:** Action, Shooter, Role-Playing, Sports
- **Score impact:** critic scores moderately correlate with sales; user scores correlate weakly
- **Hypotheses:** user score differences confirmed between XOne vs PC and Action vs Sports

---

## 🔭 What I would do next (ML-focused)

- Build a **forecasting model** for 2017 sales by platform/genre
- Add **feature importance analysis** for sales drivers
- Validate insights with **cross-validation** and **holdout years**

---

## 📬 Contact

Let’s connect: [LinkedIn](https://linkedin.com/in/your-profile) • your.email@example.com
