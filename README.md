# EV Charging Behavior Analysis in Indian Cities 🚗⚡

Exploratory Data Analysis (EDA) and statistical investigation of Electric Vehicle charging behavior across major Indian cities using Python.

---

## 📌 Project Overview

This project analyzes Electric Vehicle (EV) charging station usage across Indian cities to explore patterns in energy consumption and understand how urban environments influence charging behavior.

The analysis combines:

* Exploratory Data Analysis (EDA)
* Statistical testing
* Pivot table analysis
* Data visualization

to uncover operational insights for EV infrastructure planning.

---

## 🔍 Key Business Questions

* Does city type (Commercial vs. Residential) significantly affect energy consumption?
* How does vehicle type influence charging demand across different cities?
* Can broad city classification accurately predict charging behavior?

---

## 🛠️ Tech Stack

### Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy

### Statistical Methods

* Hypothesis Testing (Independent T-Test)
* Pivot Tables
* Crosstab Analysis
* Descriptive Statistics

---

## 📈 Key Insights

### The Correlation Paradox

Initial statistical testing showed no significant relationship between city type and energy consumption.

This suggests that broad classifications such as “Commercial” and “Residential” are too generalized to explain EV charging behavior accurately.

---

### Geographical Deep-Dive

Using Pivot Tables revealed hidden patterns inside the data:

* Kolkata showed unusually high bike energy consumption compared to other cities.
* Delhi recorded relatively lower bike consumption despite being a major commercial center.
* Trucks and buses dominated charging loads in specific urban regions regardless of city classification.

These findings suggest that:

> Vehicle distribution and local infrastructure characteristics may influence charging demand more than city labels themselves.

---

## 💡 Actionable Recommendation

Infrastructure planning should focus on:

* Vehicle distribution patterns within each city
* Local traffic behavior
* Geographic and urban characteristics

For example:

* Cities with dense or narrow urban layouts may benefit from smaller distributed charging points for bikes.
* Metropolitan regions with high heavy-vehicle demand may require larger high-capacity charging stations.

---

## 📊 Visualizations

### Energy Consumption by City Type

<img width="300" height="250" alt="image" src="https://github.com/user-attachments/assets/e610dbc2-2215-4c29-b477-df43297acd1a" />

### Average Energy Consumption by City

<img width="300" height="250" alt="image" src="https://github.com/user-attachments/assets/4eaabc3f-dd66-4530-9a1e-3d22cb714c27" />

---

## 💡 What I Learned

This project taught me that non-significant statistical results are still valuable insights.

The analysis also showed how deeper segmentation using Pivot Tables can reveal patterns hidden behind overall averages.

---

## 📂 Repository Structure

```bash
├── Notebooks/
│   └── EV_Charging_Analysis.ipynb
│
├── Data/
│   └── dataset.csv
│
├── Visuals/
│   └── charts and plots
│
└── README.md
```
