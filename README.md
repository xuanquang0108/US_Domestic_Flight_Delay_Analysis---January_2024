# ✈️ US Domestic Flight Delay Analysis - January 2024

## Project Overview

This project conducts an in-depth **Exploratory Data Analysis (EDA)** on US domestic flight data from January 2024. The primary goal is to **identify, quantify, and visualize the core drivers of flight delays**, turning raw operational data into clear, **Actionable Insights** for both airlines and passengers.

---

## Key Findings & Quantifiable Outcomes

The analysis clearly quantifies the impact of each delay factor on overall flight schedule disruptions:

* **Dominant Factor (Chain Delay)**: **Last Aircraft Delay (Delay_LastAircraft)** is the single largest cause, accounting for an overwhelming **54.7%** of all measured delays. This highlights the critical nature of the 'domino effect' in airline scheduling.
* **Carrier Operations**: **Carrier Delay (Delay_Carrier)**, linked to internal issues (e.g., maintenance, crew), contributes **22.9%**.
* **Systemic Issues**: **National Air System Delay (Delay_NAS)**, caused by air traffic congestion or external factors, accounts for **18.4%**.
* **Minimal Impact**: **Weather (3.9%)** and **Security (0.1%)** had comparatively minor impacts during the analyzed period.

### Actionable Insights

* **For Airlines**: Focus efforts on **improving aircraft turnaround time** to effectively break the chain of the 54.7% dominant delay factor.
* **For Passengers**: The highest risk of delay (especially mid-week) stems from **Delay_LastAircraft**. Checking the status of the aircraft's preceding flight can be a strong predictor of potential delays.

---

## Technical Skills & Tools

| Category | Tools & Libraries | Techniques |
| :--- | :--- | :--- |
| **Programming** | Python | Data Processing, Statistical Analysis. |
| **Libraries** | **Pandas, NumPy** | Data Manipulation, Cleaning, and Aggregation. |
| **Visualization** | **Plotly Express**, Matplotlib, Seaborn | Interactive Visualization, Exploratory Data Analysis (EDA). |
| **Methodology** | Data-Driven Storytelling | Transforming statistical data into clear business narratives. |

---

## Repository Structure

| File | Description |
| :--- | :--- |
| **`US Flights Jan, 2024.ipynb`** | **The complete Jupyter Notebook** containing all code for data cleaning, EDA, quantitative delay analysis, and final insight extraction. |
| `README.md` | Project summary, key findings, and technical stack. |
| `US Flight Jan, 2024.csv` | The raw dataset used for the analysis. |

---

## View the Full Analysis Notebook

Click the badge below to explore the detailed analysis steps, visualizations, and code execution directly on Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1zm-2ex_r9Sz8o7x4EuCsExPH8zVMLlmh?usp=drive_link)
