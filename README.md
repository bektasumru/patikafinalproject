✈️ Airline Passenger Satisfaction – Project

About the Project
In this project, the Airline Passenger Satisfaction dataset was analyzed through the following steps:

-statistical summary,

-missing value analysis,

-outlier detection (using IQR & capping),

-visualizations for numerical and categorical variables.

Purpose → To identify the key factors affecting passenger satisfaction and highlight potential areas for improvement.

## Dataset Overview

| Attribute | Value |
|-----------|-------|
| Source    | Kaggle – Airline Passenger Satisfaction |
| Rows      | 103,904 |
| Columns   | 24 |
| Target    | `satisfaction` (Satisfied / Neutral or Dissatisfied) |


## Analysis Steps

| Step | Description |
|------|-------------|
| 1. Data Loading | The dataset was imported using pandas from a `.csv` file. |
| 2. Statistical Summary | `describe()` was used to view the mean, median, and min–max values. |
| 3. Missing Values | Only the `Arrival Delay in Minutes` column had 310 missing values; these were filled using the column median. |
| 4. Outlier Detection | Outliers were detected using the IQR method and capped to boundary values. |
| 5. Visualization | Histograms, boxplots, and bar charts were created using Matplotlib & Seaborn. |
| 6. Insights | Online Boarding, Inflight Entertainment, and Seat Comfort emerged as the key factors affecting satisfaction. |



