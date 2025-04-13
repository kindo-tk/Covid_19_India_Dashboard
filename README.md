# 🦠 Covid-19 India Dashboard (2020–2021)

![Covid_19_dashboard](https://github.com/kindo-tk/Covid_19_India_Dashboard/blob/main/Covid_19_dashboard.png)

**Created by:** Tufan Kundu
**Tool Used:** Tableau  
**Data Range:** 30th January 2020 – 11th August 2021  
**Data Sources:** 5 different but related datasets + `.shp` file for map visualization
**Live Dashboard:** [View on Tableau Public](https://public.tableau.com/app/profile/tufan.kundu/viz/covid_19_dashboard_17445657158090/Covid-19IndiaDashboard?publish=yes)

---

## Dashboard Overview

This Tableau dashboard provides a comprehensive, multi-dimensional analysis of the COVID-19 situation in India, focusing on key metrics such as total deaths, vaccination trends, demographic impact, and testing infrastructure across states.

---

## Key Insights

- **Maharashtra** recorded the highest number of deaths and had the largest number of ICMR-approved testing labs (39).
- The **20-29 age group** was the most affected (25.18%), followed by the 30-39 age group (21.38%).
- **Males (66.76%)** were more affected compared to females (33.24%).
- **CoviShield** accounted for the majority of vaccine doses (over 61.9 billion), followed by **Covaxin** and **Sputnik V**.
- A clear disparity was observed between first and second doses administered, indicating the early emphasis on single-dose coverage.
- The second wave (April–June 2021) saw a sharp rise in confirmed and death cases across the country.
- State-wise visualization helps identify regional variations in deaths and infrastructure, supporting data-driven resource allocation.

---

## Visualizations Used & Rationale

| Visualization | Purpose |
|---------------|---------|
|  **Choropleth Map** (`.shp` file) | Visualize **total Covid-19 deaths by state**. Used `.shp` for better regional accuracy and offline rendering. |
|  **Horizontal Bar Chart** | Show **ICMR testing labs by state**, highlighting healthcare infrastructure. |
|  **Line Chart** | Depict **trends in confirmed, cured, and death cases over time** (Jan 2020 – Sept 2021). |
|  **Stacked Bar Chart** | Compare **first vs second dose administration** numbers for vaccination progress. |
|  **Donut Chart** | Show **age group distribution** of affected individuals, useful for demographic analysis. |
|  **Pie Chart** | Illustrate **gender-wise distribution** of Covid-19 cases. |
|  **Bar Chart** | Represent **vaccination doses administered by vaccine type** (CoviShield, Covaxin, Sputnik V). |

---

## Why a `.shp` File Was Used Instead of Tableau’s Default Map

Using a `.shp` file for the India map provided several advantages:

-  More **accurate state boundaries** (especially for J&K, Northeast)
-  Better **alignment with the dataset’s state-level death records**
-  Full **customization control** over styling and labels
-  Ensures **offline compatibility** and consistent rendering
-  Overcomes limitations in Tableau’s built-in geographic roles for Indian regions

---

##  Files Included

- `covid_19_dashboard.twbx` – Tableau workbook file  
- `Covid_19_dashboard.png` – Static image of the dashboard  
- `README.md` – This documentation file

---

## Note

This dashboard is built using real data for academic and analytical purposes. All visualizations are static in this repository. For interactive exploration, open the `.twbx` file using Tableau Desktop.

---


## Contact Information

For any queries or feedback, feel free to reach out:

- <a href="https://www.linkedin.com/in/tufan-kundu-577945221/">Tufan Kundu (LinkedIn)</a>  
- Email: tufan.kundu11@gmail.com
