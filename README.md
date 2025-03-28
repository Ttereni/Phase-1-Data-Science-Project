# Phase-1-Data-Science-Project
Project Overview

## 📌 Project Overview
This project analyzes aviation accidents to assess risk factors associated with aircraft incidents. Using data analysis and visualization techniques, we explore accident trends, fatality rates, and geographical distributions to provide actionable insights.

## 🎯 Objectives
1. **Analyze Accident Trends Over Time** – Identify patterns in aviation incidents from historical data.
2. **Assess High-Risk Locations** – Investigate which states have the highest number of accidents.
3. **Evaluate Fatality Rates** – Examine the severity of aviation incidents and factors influencing survival.
4. **Provide Data-Driven Recommendations** – Offer insights for improving aviation safety.

📂 Dataset
We use the **Aviation Accident Database** containing aviation accident reports from **1948 to 2024** with key features:
- **Aircraft Details:** Make, Model, Number of Engines, Engine Type.
- **Accident Metadata:** Date, Location, Weather Condition, Phase of Flight.
- **Injury Data:** Number of Fatal, Serious, and Minor Injuries.
- **Geographical Information:** State, Country.

## 🛠 Tools & Libraries
- **Python** – Core language for data processing
- **Pandas & NumPy** – Data cleaning and transformation
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** – Interactive data analysis environment

## 🔄 Data Preprocessing
1. **Dropped Columns:** Removed columns with over 50% missing values.
2. **Renamed Columns:** Standardized column names for better readability.
3. **Date Processing:** Converted event dates to datetime format and extracted years.
4. **Missing Values:** Handled missing values by replacing or dropping where necessary.
5. **Extracted Location Data:** Parsed state information from location data.
6. **Created Additional Features:** Computed total people involved and fatality rate.

## 📊 Key Insights & Visualizations
### 1️⃣ Accident Trends Over Time
- Line chart showing aviation accident trends from **1982 onwards**.
- This helps in identifying peak accident periods.
- ![image](https://github.com/user-attachments/assets/f99c6f5b-c88b-41fb-8de7-2e613af677a9)


### 2️⃣ Top 10 States with Most Accidents
- Bar chart highlighting the states with the highest number of aviation incidents.
- ![image](https://github.com/user-attachments/assets/07ad6039-8391-46fc-be6a-cb07997787d1)


### 3️⃣ Fatality Rate Per Year
- Bar chart analyzing fatality percentages over time, providing insight into aviation safety improvements.

## 📈 Sample Visualizations
| Visualization | Description |
|--------------|-------------|
| ![Accident Trends](images/accidents_per_year.png) | Trends of aviation accidents per year |
| ![Accidents by State](images/accidents_by_state.png) | Top 10 states with most accidents |
| ![Fatality Rate](images/fatality_rate.png) | Fatality rate per year |

## 💾 Data Export
- Cleaned dataset saved as **`Aviation_Data_Clean.csv`** for further analysis.

## 📝 Conclusions & Recommendations
### 🔍 Conclusions
- The highest number of accidents occur during **takeoff and landing** phases.
- **Weather conditions** significantly impact accident frequency.
- **Multi-engine aircrafts** tend to have higher survival rates.

### ✅ Recommendations
- Improve **pilot training** for critical flight phases.
- Invest in **advanced landing and takeoff safety measures**.
- Consider **engine redundancy** for enhanced aircraft safety.
- Monitor **weather conditions** closely before flights.

## 📜 License
This project is open-source under the **MIT License**.

## 👥 Contributors
- **Your Name** – Data Analysis & Visualization

Feel free to contribute by submitting issues or pull requests! 🚀
