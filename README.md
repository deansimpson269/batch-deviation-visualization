# Batch Deviation Visualization: Severity & Impact Trends

This project analyzes synthetic batch deviation data from a GMP (Good Manufacturing Practice) manufacturing process using **Python**, specifically `pandas`, `matplotlib`, and `seaborn`.

The goal is to visualize patterns in deviation **severity**, **impact**, and **root cause classification**, helping quality and compliance teams better understand trends in their deviation logs.

---

## Overview

This Jupyter Notebook walks through a complete exploratory data analysis (EDA) pipeline:

- Data import and cleaning
- String normalization to prevent category duplication
- Summary statistics and value counts
- Visualizations using bar charts and heatmaps

All code was written and executed in a local Jupyter environment.

---

## Key Visuals

- **Top Deviation Types** *(bar chart)*
- **Severity Distribution** *(red horizontal bar chart)*
- **Impact Distribution** *(green horizontal bar chart)*
- **Heatmap**: Severity vs. Impact *(correlation heatmap with annotations)*

---

## Insights

- **Major deviations** are most often associated with **reprocessing required**.
- **Critical deviations** frequently result in **scrapped batches** or **delayed release**.
- A **small subset of deviation types** accounts for most issues — suggesting SOP updates or calibration may yield high-leverage improvements.

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/deansimpson269/batch-deviation-visualization.git
