# COVID-19-Data-Analysis-Project.
An in-depth analysis of the Our World in Data COVID-19 dataset using Python, Pandas, and Plotly.
# COVID-19 Global Data Analysis 🦠

![Language](https://img.shields.io/badge/Language-Python-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

A comprehensive analysis of the Our World in Data COVID-19 dataset to uncover trends, visualize the global impact, and analyze the relationship between vaccination rates and health outcomes.

---

## 📖 Overview

This project provides an in-depth exploratory data analysis of the global COVID-19 pandemic. The primary goal was to practice and showcase data analysis skills, including data cleaning, feature engineering, and advanced data visualization. The analysis moves from a high-level global overview to a more detailed look at individual country trajectories and the impact of vaccination campaigns.

---

## ✨ Key Features & Insights

* **Data Cleaning:** The raw dataset was systematically cleaned by handling missing values and filtering out non-country entities (like continents and income groups) to ensure analytical accuracy.
* **Trend Analysis:** A 7-day rolling average was applied to daily new cases and deaths to smooth out noise and clearly identify the distinct "waves" of the pandemic in various nations.
* **Geospatial Visualization:** An interactive choropleth map was created with Plotly to visualize the total number of confirmed cases, providing an intuitive understanding of the pandemic's global footprint.
* **Correlation Analysis:** A dual-axis chart was used to investigate the relationship between the rise in vaccination rates and the decline in new deaths, highlighting the apparent effectiveness of vaccination programs.

---

## 📊 Visualizations

Here are some of the key visualizations from the analysis:

### Global Distribution of Total Cases
An interactive map showing the total confirmed cases per country. You can hover over a country to see its specific data.

<img width="823" height="525" alt="newplot (2)" src="https://github.com/user-attachments/assets/647ccfe5-88d9-473b-a437-e11b94004352" />

### New Deaths vs. Vaccination Rate in Germany
This chart compares the 7-day average of new deaths to the percentage of the population fully vaccinated, showing a strong negative correlation over time.

<img width="1348" height="709" alt="grp2" src="https://github.com/user-attachments/assets/1b3ba9f0-42b1-4585-80e1-eee2664b928f" />
