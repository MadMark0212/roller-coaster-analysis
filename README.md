# Roller Coaster Data Analysis

A data analysis project that explores trends in roller coaster rankings and performance using real-world datasets and data visualization techniques.

---

## Project Overview

This project analyzes roller coaster data from multiple datasets to uncover trends in rankings, physical characteristics, and operational status.

The analysis focuses on answering questions such as:

* How do roller coaster rankings change over time?
* What factors (height, speed, inversions) define top coasters?
* Are there relationships between coaster features?

---

## Datasets

This project uses three datasets:

* **Golden Ticket Awards (Wood)**
* **Golden Ticket Awards (Steel)**
* **Captain Coaster Dataset**

These datasets include information such as:

* Rankings by year
* Park location
* Manufacturer
* Height, speed, and length
* Number of inversions
* Operating status

---

## Technologies Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

---

## Key Features

*  Line plots showing ranking trends over time
*  Comparison of multiple roller coasters
*  Histograms for distribution analysis
*  Bar charts for park-level insights
*  Pie charts for operating vs closed coasters
*  Scatter plots for feature relationships

---

## Key Insights

* Some roller coasters consistently rank highly over multiple years
* Taller roller coasters tend to reach higher speeds
* Most roller coasters have relatively few inversions
* There is a noticeable number of closed coasters, indicating industry turnover

---

## Project Structure

```
roller-coaster-analysis/
│
├── data/               # Datasets used for analysis
├── notebook/           # Jupyter Notebook with full analysis
├── images/             # Saved visualizations (optional)
├── requirements.txt
└── README.md
```

---

## How to Run This Project

1. Clone the repository:

```
git clone https://github.com/yourusername/roller-coaster-analysis.git
cd roller-coaster-analysis
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Open Jupyter Notebook:

```
jupyter notebook
```

4. Run:

```
notebook/roller_coaster_analysis.ipynb
```

---

## Notes

* Missing values were removed using `.dropna()`
* Outliers were filtered to improve visualization clarity
* Duplicate coaster names were handled using both name and park

---

## Future Improvements

* Add interactive visualizations (Plotly or Dash)
* Perform deeper statistical analysis
* Build a dashboard for real-time exploration

---

## What This Project Demonstrates

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Data visualization techniques
* Writing reusable Python functions
* Structuring a professional data project

---

