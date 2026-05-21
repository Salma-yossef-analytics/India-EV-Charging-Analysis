# India-EV-Charging-Analysis
Exploratory Data Analysis (EDA) of Electric Vehicle charging patterns in India using Python
India EV Charging Analysis 🚗⚡

📌 Project Overview
This project provides an in-depth analysis of Electric Vehicle (EV) charging station usage across major Indian cities. The goal was to identify patterns in energy consumption and investigate how urban environments influence charging behavior.

🔍 Key Business Questions
Is there a direct correlation between city type (Residential vs. Commercial) and energy consumption?

How does vehicle type (Bike, Car, Bus, Truck) affect the charging load in different geographical locations?

🛠️ Tech Stack
Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn

Statistical Methods: Correlation Analysis, T-tests (Hypothesis Testing), Pivot Tables.

📈 Key Insights (The Story)
The Correlation Paradox: Initial statistical tests showed a weak correlation between city type and energy consumption, suggesting that the "Residential/Commercial" label is too broad to predict load.

Geographical Deep-Dive: By using Pivot Tables, I discovered that Kolkata (a mountainous/hilly region) shows significantly higher energy consumption for Bikes, whereas in Delhi, bike consumption is at its lowest.

Actionable Recommendation: Infrastructure planning should prioritize small, frequent charging points for bikes in narrow, hilly terrains like Kolkata, while focusing on high-capacity stations for larger vehicles in metropolitan hubs.

📂 Repository Structure
Notebooks/: Contains the Jupyter Notebook with the full analysis.

Data/: Dataset information and sources.

Visuals/: Key charts and correlation matrices.
