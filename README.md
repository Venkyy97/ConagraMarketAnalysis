# ConagraMarketAnalysis
# Meat Substitutes Market Analysis Project

## Overview
This project is part of a **Predictive Analytics for Data Science** course at the University of Texas, Dallas. Our group analyzed the North American meat substitutes market, focusing on **Gardein**. The goal was to uncover trends, pricing strategies, and opportunities for Gardein to compete with other key players like **Beyond Meat** and **Impossible Foods**. 

Through data-driven insights, we provided recommendations on optimizing discount strategies, product expansion, and packaging to enhance Gardein's market position.

## Project Objectives
The primary objective of the project was to:
- Identify market trends in the meat substitute industry.
- Analyze Gardein’s competitive position against Beyond Meat and Impossible Foods.
- Provide actionable insights to improve Gardein’s market share and profitability.

## Dataset
We used a dataset containing market share, pricing trends, product forms, and discount strategies across leading brands in the meat substitutes industry. The data was visualized and analyzed using **Python** and libraries such as **Pandas**, **Matplotlib**, and **Scikit-learn**.

Key brands analyzed include:
- **Beyond Meat**
- **Impossible Foods**
- **Morningstar Farms**
- **Gardein**

## Exploratory Data Analysis (EDA)
We performed an Exploratory Data Analysis (EDA) to uncover insights on the following:
- **Market share trends**: We compared Gardein with other major players in the market.





- **Pricing analysis**: Gardein’s price trends were analyzed and compared with competitors.
- **Discount strategies**: Analyzed how Gardein and its competitors use discounts and their impact on market share.

### Sample Visualizations:
1. **Market Share by Brand**  
   A graph that highlights the market share distribution among leading brands. You can see how Gardein compares with brands like Beyond Meat and Impossible Foods.
![image](https://github.com/user-attachments/assets/c75ee437-7e56-47db-bc6e-3f57df9d87a5)
2. **Pricing Trends**  
   This graph shows pricing trends of Gardein, Beyond Meat, and Impossible Foods over the past two years.
   ![image](https://github.com/user-attachments/assets/7082d55c-face-4b5e-8857-8e2bb199f047)


4. **Form Analysis**  
   A visualization that shows which product forms (e.g., burgers, tenders, fillets) contribute the most to dollar sales for each brand.
![image](https://github.com/user-attachments/assets/22905eb3-5378-4297-bf58-49993a923c8d)

## Methodology
### Data Preprocessing
We used several techniques to clean and preprocess the data:
- **Missing value imputation** for price and discount-related columns.
- **Standardization** of column names and formats.
- **Column selection** by removing irrelevant columns and focusing on essential variables.

### Regression Analysis
We ran regression models to study the impact of price changes on market share across different regions. The key findings include:
- A price increase for Gardein is associated with a significant drop in market share, unlike competitors like Impossible Foods, which gained market share despite price increases.

### Recommendations
Based on the analysis, we recommended several strategies for Gardein to improve its competitive standing:
1. **Packaging**: Shift towards vacuum-packed products to enhance perceived freshness.
2. **Family Pack Expansion**: Introduce family-sized packaging options to cater to larger households.
3. **Discount Strategy**: Focus discounts on fewer products with deeper price cuts.
4. **Form Expansion**: Explore more diverse product forms that dominate the market.

## Machine Learning Models
We used several predictive models to forecast future market trends and the impact of various strategies. **Linear Regression** and **Logistic Regression** models were employed to predict market share based on pricing and form expansion.

## Technologies Used
- **Python** (Pandas, Matplotlib, Seaborn, Scikit-learn)
- **Jupyter Notebooks** for EDA and analysis
- **Regression Analysis** to predict price elasticity and market trends
- **Visualization Tools** for presenting insights

## Key Results
- **Beyond Meat** and **Impossible Foods** are Gardein's primary competitors, with both brands taking a larger share of the market.
- Gardein’s pricing strategy needs refinement, as price increases disproportionately impact its market share.

## Recommendations for Future Work
- Implement predictive models to continuously monitor market share trends.
- Further explore the impact of marketing campaigns on brand visibility and market penetration.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/meat-substitute-market-analysis.git
