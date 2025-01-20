# NYC Airbnb Data Visualization and Insights

This project analyzes the New York City Airbnb market using the **AB_NYC_2019.csv** dataset, leveraging Python visualizations and Power BI dashboards. The aim is to provide stakeholders with actionable insights on rental trends, pricing, and neighborhood dynamics.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Analysis and Visualizations](#analysis-and-visualizations)
- [Power BI Dashboard](#power-bi-dashboard)
- [How to Use](#how-to-use)
- [Results and Insights](#results-and-insights)
- [Future Work](#future-work)

---

## Introduction
Airbnb has transformed the hospitality industry, especially in vibrant cities like New York. This project dives deep into the NYC Airbnb market, focusing on:
- Rental patterns and pricing.
- Neighborhood-specific trends.
- Revenue potential for hosts and affordability for guests.

## Dataset
The primary dataset, **AB_NYC_2019.csv**, sourced from [Kaggle](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data), includes:
- 48,895 Airbnb listings.
- Attributes like price, location, room type, and reviews.
- Detailed neighborhood data across NYC's five boroughs.

## Analysis and Visualizations
We utilized Python libraries (Matplotlib, Seaborn, Plotly) and conducted:
- **Spatial Analysis**: Hexbin and scatter plots to map listing density and pricing trends.
- **Temporal Analysis**: Line charts for borough-wise price trends.
- **Text Analysis**: Word clouds highlighting listing descriptions.
- **Economic Analysis**: Combining rental income data with Airbnb metrics for profitability insights.

Interactive Power BI dashboards complement Python visualizations for granular, real-time exploration.

## Power BI Dashboard
A dynamic dashboard showcases:
- Key metrics (total listings, average price, revenue).
- Borough-wise listing densities.
- Room type distributions and pricing tiers.
- Top-performing neighborhoods.

Explore the dashboard [here](https://app.powerbi.com/view?r=eyJrIjoiOTNhNmVmNjctMWVlYi00ZGQxLThmYjYtMjliYjNhNjI5OTk1IiwidCI6IjExMTNiZTM0LWFlZDEtNGQwMC1hYjRiLWNkZDAyNTEwYmU5MSIsImMiOjN9&embedImagePlaceholder=true).



## How to Use
1. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
2. Run the Jupyter Notebook to explore Python visualizations.
3. Open the Power BI dashboard link for interactive insights.

## Results and Insights
### Key findings include:
- **Manhattan** leads in price and density; **Staten Island** offers the highest profit margins.
- **Private rooms** dominate affordable listings, while **entire homes** cater to luxury stays.
- Listings with **moderate pricing** attract the highest reviews, balancing affordability and guest satisfaction.

---

## Future Work
- **Incorporate shapefiles** for precise geographic analysis.
- Use **sentiment analysis** on guest reviews for qualitative insights.
- Develop **predictive models** for market trends.
