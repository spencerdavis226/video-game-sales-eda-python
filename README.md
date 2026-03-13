# Video Game Sales Exploratory Data Analysis (Python)

This project explores historical video game sales data using Python to identify trends in genres, regional markets, and publisher performance.

The goal is to demonstrate **clean exploratory data analysis (EDA) practices** using common data analysis tools such as pandas, NumPy, matplotlib, and seaborn.

---

## Project Overview

The dataset contains global video game sales from **1980–2016**, including regional breakdowns for North America, Europe, Japan, and other markets.

This analysis focuses on answering several business-style questions:

- Which **genres** have historically been the most popular?
- How have **video game sales evolved over time**?
- How do **regional markets differ** in their preferences?
- Which **publishers** appear to be the strongest competitors?

The project emphasizes clear data cleaning, reproducible analysis, and well-structured exploratory insights.

---

## Tools and Libraries

- Python
- pandas
- NumPy
- matplotlib
- seaborn
- Jupyter Notebook

---

## Repository Structure

```
video-game-sales-eda-python/
│
├── data/
│   ├── raw/                # Original dataset
│   └── processed/          # Cleaned dataset
│
├── notebooks/
│   ├── data_inspection.ipynb
│   ├── data_cleaning.ipynb
│   └── eda_analysis.ipynb
│
├── requirements.txt        # Project dependencies
└── README.md
```

---

## Data Cleaning

The cleaning process focuses on preparing the dataset for reliable analysis while avoiding unnecessary assumptions. Key steps include:

- Removing duplicate rows
- Dropping non-analytical columns
- Handling missing categorical values
- Removing rows with incomplete sales data
- Filtering invalid or missing release years

The cleaned dataset is saved for reproducible analysis.

---

## Example Analyses

The EDA explores several aspects of the video game market, including:

- Sales trends over time
- Genre popularity
- Regional sales differences
- Publisher performance

Visualizations are created using **matplotlib** and **seaborn** to highlight key patterns in the data.

---

## How to Run the Project

1. Clone the repository

```
git clone https://github.com/spencerdavis226/video-game-sales-eda-python
cd video-game-sales-eda-python
```

2. Create a virtual environment and install dependencies

```
pip install -r requirements.txt
```

3. Open the notebooks

```
jupyter notebook
```

---

## Project Purpose

This project is part of a data analytics portfolio and demonstrates:

- structured exploratory data analysis
- transparent data cleaning practices
- clear and reproducible Python workflows

The focus is on producing **clean, interpretable insights** rather than building predictive models.
