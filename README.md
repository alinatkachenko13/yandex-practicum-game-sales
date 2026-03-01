# 🎮 Video Game Sales Analysis

> Exploratory analysis of historical game sales data for planning an advertising campaign for the online store «Streamchik»

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)

---

## 📋 About the Project

This project is a **full exploratory data analysis (EDA)** for an online game store planning an advertising campaign for 2017. Based on a dataset with sales history (~17K records), it covers:

- **Data preparation** — cleaning, handling missing values, feature engineering
- **Exploratory analysis** — visualizations, pattern discovery across platforms, genres, and regions
- **Statistical analysis** — hypothesis testing with t-test (scipy)
- **Business recommendations** — data-driven campaign plan for NA, EU, and JP

---

## 🛠 Tech Stack

| Category          | Technologies        |
|-------------------|---------------------|
| **Language**      | Python 3            |
| **Data**          | pandas              |
| **Visualization** | matplotlib, seaborn |
| **Statistics**    | scipy.stats         |
| **Environment**   | Jupyter Notebook    |

---

## 🧠 Skills Demonstrated

| Area                          | What was done                                                                                               |
|-------------------------------|-------------------------------------------------------------------------------------------------------------|
| **Data Preprocessing**        | Type conversion, handling missing values (median imputation by groups), duplicate removal, feature creation |
| **Exploratory Data Analysis** | Distribution analysis, correlations, time series, segmentation by platforms and genres                      |
| **Statistical Analysis**      | T-test for comparing samples, significance level α                                                          |
| **Visualization**             | Boxplots, bar charts, scatter plots to communicate findings                                                 |
| **Product Thinking**          | User profiles by region, business recommendations                                                           |

---

## 🚀 Getting Started

### Install dependencies

```bash
pip install -r requirements.txt
```

### Data setup

Place `games.csv` in the `datasets/` directory or update the path in the notebook:

```python
# Default: data = pd.read_csv('/datasets/games.csv')
# For local run: data = pd.read_csv('datasets/games.csv')
```

### Run the analysis

```bash
jupyter notebook game_sales_analysis.ipynb
```

Run all cells (Kernel → Restart & Run All).

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

## 📊 Key Findings

- **Relevant data period:** 2006–2016 (platform lifecycle ~6 years)
- **Promising platforms for 2017:** PS4, Xbox One, WiiU, PSV, 3DS
- **Leading genres:** Action, Shooter, Role-Playing, Sports
- **Score impact:** `critic_score` moderately correlates with sales; `user_score` — weakly
- **Statistical hypotheses:** User score differences confirmed between platforms (XOne vs PC) and between genres (Action vs Sports)

---

## 📬 Contact

Happy to discuss the project and further development — reach out on [LinkedIn](https://linkedin.com) or by email.
