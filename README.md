# NDTA631 Group Assignment – South Africa: Diet, GDP & Food Security Trends

## 📌 Project Overview
This project explores the relationship between **GDP per capita, food affordability, undernourishment, and the cost of a healthy diet** in South Africa. Using multiple datasets, we clean, merge, and analyze the data to identify patterns and insights into how economic performance impacts food security and nutrition.  

Our analysis covers the period **2017–2024** and uses **Python (Pandas, Matplotlib, Seaborn, NumPy)** for data preparation, visualization, and insights.

---

## 📂 Datasets Used
The following datasets were combined for our analysis:

1. **Cost_of_a_healthy_diet.csv** – Daily cost of a healthy diet (PPP$/day).  
2. **GDP_per_capita.csv** – GDP per capita (constant 2017 international $).  
3. **Number_of_undernourished_people.csv** – Population undernourished (in millions).  
4. **Unable_to_affordhealthy_diet.csv** – People unable to afford a healthy diet (in millions).  

All datasets were filtered for **South Africa** and merged for comparative analysis.

---

## 🔎 Key Steps in the Notebook
1. **Data Loading & Cleaning**
   - Imported datasets using Pandas.  
   - Checked for missing values and handled inconsistencies.  
   - Renamed columns for clarity.  
   - Filtered dataset to focus on South Africa.  

2. **Data Preparation**
   - Generated descriptive statistics for each dataset.  
   - Created a merged dataset (`merged_clean_data`) for analysis.  

3. **Visualization & Analysis**
   - **Line Charts**: Trends in GDP, cost of diet, affordability ratio, undernourishment.  
   - **Bar Chart**: GDP per capita across selected years.  
   - **Area Chart**: Undernourished population trend.  
   - **Scatter/Bubble Plot**: GDP vs affordability ratio, with bubble size showing population unable to afford diets.  
   - **Histogram**: Distribution of affordability ratios.    
   - **Comparison Line Plot**: Undernourished vs unable to afford a healthy diet.

---

## 📊 Key Insights
- **GDP per Capita**: Stable until 2019, dropped sharply in 2020 due to COVID-19, partially recovered, but declined again in 2023–24, showing fragile recovery.  
- **Undernourishment**: Declined before 2020 but increased during pandemic years, showing vulnerability in food access.  
- **Affordability**: Higher GDP generally reduces affordability ratios, but inequality means many still cannot afford healthy diets.  
- **Distribution of Affordability**: Some households spend a much larger share of income on food, showing inequality.  
- **Cost of Healthy Diet**: While average costs remain steady, volatility creates challenges for low-income households.  
- **Undernourished vs Unable to Afford**: More people cannot afford healthy diets than those who are undernourished, showing a gap between food **quantity** and **quality**.

---

## 🛠️ Technologies Used
- **Python**  
- **Pandas** (data manipulation)  
- **Matplotlib & Seaborn** (visualizations)  
- **NumPy** (numerical operations)  
- **Jupyter Notebook** (analysis & reporting)  

---


