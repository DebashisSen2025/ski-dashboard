# 📊 Airbnb NYC 2019 Market Analysis Dashboard

This repository contains an **Exploratory Data Analysis (EDA)** and a **Power BI dashboard** visualizing Airbnb properties in **New York City (2019)**.  
The analysis highlights pricing patterns, demand distribution, borough insights, and host behavior trends.

---

## 🛠️ Tools & Technologies Used

- 🐍 Python (Pandas, NumPy, visualization)  
- 📊 Power BI Desktop (interactive dashboard)  
- 📁 Excel / CSV data handling  
- 🧠 EDA & insights storytelling

---

## 📁 Repository Structure

```
ski-dashboard/
├── Airbnb.ipynb                # Jupyter Notebook for data cleaning & EDA
├── Listing details.pbit        # Power BI dashboard file
├── ecommerce_data_excel.xlsx   # Airbnb NYC 2019 dataset
├── Screenshot*.jpg             # Dashboard preview image
└── README.md                  # Project documentation
```

---

## 📈 Project Overview

The goal is to analyze the **Airbnb listings market in NYC (2019)** and provide insights into:

- 🏙️ Borough wise distribution of listings  
- 💰 Price range and pricing trends  
- 📊 Demand signals (most/least active areas)  
- 👤 Host booking behavior  
- 🔍 Correlations between price, location, and demand

---

## 🔍 Key Insights (Example)

- Manhattan and Brooklyn have the highest number of listings and ADR (Average Daily Rate)  
- Some boroughs show higher seasonal demand trends during summer months  
- Pricing varies significantly between entire home listings vs shared/ private rooms  
- Certain neighborhoods show higher occupancy rates and revenue potential

---

## 🖥️ Dashboard Visuals Included

- 🗺️ Geospatial map of listings  
- 📊 Price distribution histogram  
- 📉 Borough comparison bar charts  
- 📆 Seasonal demand trend lines

*(Include screenshots here for better presentation)*

---

## 🧪 How to Use

### 🧩 Open the Notebook
1. Install Python libraries:
```bash
pip install pandas matplotlib seaborn
```
2. Run the notebook:
```bash
jupyter notebook Airbnb.ipynb
```

### 📊 Open the Dashboard
1. Open **Power BI Desktop**  
2. Load the file `Listing details.pbit`  
3. Interact with filters and visuals to explore data insights

---

## 📊 Dataset Description

The dataset includes Airbnb listings for NYC (2019) with fields like:

- `listing_id`, `borough`, `neighborhood`
- `price`, `minimum_nights`
- `number_of_reviews`
- `availability_365`, etc.

*(Add a short data dictionary here)*

---

## 📦 Future Enhancements

- Add SQL data pipeline for ETL  
- Add automated refresh (Power BI Service)  
- Add deeper time series forecasting analysis  
- Add geospatial clustering for pricing zones

---

## 👤 Author

**Debashis Sen**  
Aspiring Data Analyst  
Skills: SQL | Python | Power BI | EDA | Data Visualization

⭐ If you find this useful, please give a star!  
