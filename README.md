# 🏡 Real Estate Valuation Project

[![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue?logo=python)](https://www.python.org/)
[![Power BI](https://img.shields.io/badge/PowerBI-Interactive%20Dashboard-yellow?logo=powerbi)](https://powerbi.microsoft.com/)
[![Colab](https://img.shields.io/badge/Google%20Colab-Notebook-orange?logo=googlecolab)](https://colab.research.google.com/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## 📌 Project Overview

This project is part of the **Introduction to Big Data Analytics** coursework. It explores real estate property valuation using a dataset of property sales in Taiwan. The goal is to identify the key factors influencing housing prices and deliver these insights through interactive dashboards and advanced data analytics.

---

## ❓ Problem Statement

Can we predict real estate property values based on location factors, accessibility to public transportation, and neighborhood amenities to help investors and buyers make informed decisions?

**Key Questions:**
- What factors most strongly influence property prices?
- How does location accessibility affect valuation?
- Can we categorize properties by price tiers and location clusters?

---

## 🎯 Objectives

- 🔍 Analyze real estate sales data using Python (Pandas, NumPy, Seaborn, Matplotlib)
- 🧼 Clean, transform, and engineer features (e.g., accessibility score, categories)
- 📊 Build interactive visualizations in Power BI for stakeholders
- 💡 Draw actionable insights to support valuation predictions

---

## 🧪 Tech Stack

| Tool         | Purpose                                 |
|--------------|------------------------------------------|
| Python       | Data analysis & preprocessing            |
| Google Colab | Jupyter environment for coding           |
| Power BI     | Data visualization & interactive reports |
| GitHub       | Version control & reporting              |

---

## 🗃️ Dataset Description

- 📍 **Records:** 414 property transactions
- 🏠 **Features:**
  - `house_age`: Age of the house
  - `distance_to_MRT`: Distance to the nearest MRT station
  - `convenience_stores`: Number of nearby stores
  - `price_per_unit_area`: Target variable
  - `latitude`, `longitude`: Geographic info
  - Engineered fields like `age_category`, `price_category`, and `accessibility_score`

---

## 🧹 Data Preparation & Feature Engineering

- ✅ Handled missing values (none in this case)
- ✅ Created custom features:
  - **Age Category**: New, Modern, Mature, Old
  - **Distance Category**: Very Close, Close, Far
  - **Store Category**: Abundant, Some, Few
  - **Accessibility Score**: Composite metric combining proximity and amenities
- ✅ Clustered locations using k-means

---

## 📈 Exploratory Data Analysis (EDA)

Insights from Python analysis:
- 📉 Strong negative correlation between price and distance to MRT
- 🏪 Positive impact of store count on property valuation
- 🗺️ Clusters show pricing patterns by region

---

## 📊 Power BI Dashboard Highlights

✅ **Interactive Filters**:
- Year, Month
- Price Category
- Age & Store Categories
- Location Cluster

✅ **Visuals**:
- Line charts for price trends
- Scatter plot: Distance vs Price
- Geo map: Prices across coordinates
- Bar charts: Avg price by category
- Accessibility score insights

✅ **Innovative Features**:
- Tooltips with property context
- DAX formulas for calculated metrics
- Smart Narratives for AI insights
- Drill-through pages per cluster
- Bookmarks for report modes (Trend, Location, Features)

---

## 📎 Screenshots

<img width="1803" height="1190" alt="output2" src="https://github.com/user-attachments/assets/581031e1-0544-4a30-ba6c-fc4baeb826e6" />

<br> **🔍 Data Exploration**
<img width="1789" height="1190" alt="output" src="https://github.com/user-attachments/assets/b7b9383b-0779-474c-afbb-894ee7a56882" />

<br> **📊 Power BI Dashboard**
![Capture](https://github.com/user-attachments/assets/a6f28051-6d05-4c57-b0f8-c824a43c218a)


---

## 💡 Key Insights

- Houses nearer to MRT and with more nearby stores fetch higher prices.
- Newer buildings have higher valuations.
- Accessibility score is a strong predictive metric.
- Some location clusters consistently outperform others in pricing.

---

## 🛠️ Future Work & Innovations

- 🧠 Integrate ML models (e.g., Linear Regression, XGBoost) to predict prices.
- 🌐 Deploy dashboard as a Power BI web app.
- 🧭 Add satellite and map visuals for enhanced location context.
- 🤖 Use R visuals or Python scripting inside Power BI for advanced analytics.

---



## 👩‍💻 Author

**Iteka Laure Gabriella**  
📫 [ITEKA Laure Gabriella] [ID:22718] {• 🌐 [LinkedIn or GitHub Profile]  
🎓 Student, Introduction to Big Data Analytics

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

> “Turning raw housing data into actionable insights through modern analytics.”
