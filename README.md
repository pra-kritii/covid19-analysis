# covid19-analysis

# 📊 COVID-19 & Worldwide Happiness Analysis

This project investigates the relationship between COVID-19 impact and global happiness indicators. By analyzing real-world datasets from the Johns Hopkins University (COVID-19 confirmed cases) and the World Happiness Report, we explore how factors like GDP, social support, and life expectancy may correlate with pandemic outcomes.


## 📌 Objectives

- Load and preprocess two datasets:
  - COVID-19 time series data
  - World Happiness Report
- Perform exploratory data analysis (EDA)
- Merge datasets on country
- Analyze correlations between happiness metrics and COVID-19 statistics
- Visualize findings using plots and charts
- Generate insights and summary


## 📁 Project Structure


📦 covid-happiness-analysis
├── covid19.ipynb                  # Main Jupyter notebook (data analysis and visualizations)
├── covid19\_Confirmed\_dataset.csv # COVID-19 dataset (confirmed cases by country/date)
├── worldwide\_happiness\_report.csv # World Happiness Report dataset
├── report.html                   # (Optional) Exported visual summary
└── README.md                     # Project documentation



## 📊 Datasets

### 1. COVID-19 Dataset
- Source: Johns Hopkins University CSSE
- Content: Daily confirmed COVID-19 cases by country (up to April 2020)

### 2. World Happiness Report
- Source: [https://worldhappiness.report](https://worldhappiness.report)
- Indicators: Happiness Score, GDP per capita, Social Support, Life Expectancy, Freedom, Generosity, Corruption


## 🧰 Tools & Technologies

- Python
- Jupyter Notebook
- Libraries:
  - `pandas`, `numpy` – data manipulation
  - `matplotlib`, `seaborn`, `plotly` – data visualization


## 📈 Visualizations

- Time-series line charts of infection trends
- Correlation heatmaps
- Scatter plots of:
  - GDP vs Max Infection Rate
  - Social Support vs Total Cases
  - Life Expectancy vs COVID Metrics

## 🔍 Key Questions Answered

- Do happier countries fare better during the COVID-19 pandemic?
- How do economic and social well-being indicators correlate with COVID-19 outcomes?
- Which happiness factors are most associated with reduced infection impact?


## ✅ Outcome Summary

* Countries with higher GDP, social support, and life expectancy showed signs of **better COVID-19 outcomes**.
* Happiness alone is not a direct determinant, but related indicators (economic and healthcare strength) contribute to resilience.
* Visual patterns suggest inverse correlation between wellness metrics and infection severity.


## ✍️ Author

**Prakriti Kesharwani** <br>
GitHub: [@prakritikesharwani](https://github.com/prakritikesharwani)


