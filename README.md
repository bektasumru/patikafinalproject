✈️ Airline Passenger Satisfaction – Project

![Project Cover](visuals/airplaneproject.png)

About the Project
In this project, the Airline Passenger Satisfaction dataset was analyzed through the following steps:

-statistical summary,

-missing value analysis,

-outlier detection (using IQR & capping),

-visualizations for numerical and categorical variables.

PURPOSE → To identify the key factors affecting passenger satisfaction and highlight potential areas for improvement.

## Dataset Overview

| Attribute | Value |
|-----------|-------|
| Source    | Kaggle – Airline Passenger Satisfaction |
| Rows      | 103,904 |
| Columns   | 24 |
| Target    | `satisfaction` (Satisfied / Neutral or Dissatisfied) |


## 🔎 Analysis Steps

| Step | Description |
|------|-------------|
| 1. 📥 Data Loading | The dataset was imported using `pandas`. |
| 2. 📈 Statistical Summary | `describe()` method used to view mean, median, min–max values. |
| 3. 🔧 Missing Values | Missing data in `Arrival Delay in Minutes` was filled using the median. |
| 4. 🚨 Outlier Detection | IQR method used to identify outliers; `capping` was applied to reduce their effect. |
| 5. 📉 Visualization | Charts created using **Matplotlib** & **Seaborn** (Histograms, Boxplots, Bar Charts). |
| 6. 💡 Key Insights | Features like **Online Boarding**, **Inflight Entertainment**, and **Seat Comfort** had the strongest impact on satisfaction. |

---

## 📌 Key Findings

- 💺 **Business class** and **loyal customers** tend to report higher satisfaction.
- 📶 Areas needing improvement: **Inflight Wifi Service** and **Ease of Online Booking**.
- 📊 Delay variables (arrival/departure) had significant outliers, but were kept due to their real-world nature.

---

## 🧰 Technologies Used

- Python (pandas, numpy)
- Data Visualization (matplotlib, seaborn)
- Jupyter Notebook
- Git & GitHub

---

## 🎯 Conclusion

This project highlights the main factors affecting airline passenger satisfaction. The insights can guide airlines in enhancing service quality and targeting key areas for operational improvements.

---



