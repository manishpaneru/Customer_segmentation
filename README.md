# Customer Segmentation Analysis

## Overview
This project performs customer segmentation analysis using K-means clustering on customer data to identify distinct customer groups based on their characteristics and behaviors. The analysis helps in understanding different customer segments and their unique patterns.

## Dataset
The dataset contains customer information including:
- Customer ID
- Gender
- Age
- Annual Income
- Spending Score (1-100)
- Profession
- Work Experience
- Family Size

## Analysis Components
The analysis includes:
1. Data loading and preprocessing using pandas
2. Customer clustering using K-means algorithm
3. Visualization of clusters using various plots:
   - Scatter plot of clusters based on annual income and spending score
   - Bar charts comparing average income and spending scores across clusters
   - Cluster characteristics summary
   - Customer segmentation distribution pie chart

## Requirements
- Python 3.x
- Required libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

## Visualizations
The notebook includes several visualizations:
- Cluster scatter plot showing the distribution of customers based on income and spending
- Bar charts comparing key metrics across clusters
- Summary charts showing cluster characteristics
- Pie chart showing the distribution of customers across segments

## Usage
1. Ensure all required libraries are installed
2. Open the Jupyter notebook `EDA.ipynb`
3. Run all cells to perform the analysis and generate visualizations

## Results
The analysis identifies distinct customer segments based on their income and spending patterns, helping to understand:
- Customer spending behaviors
- Income distribution patterns
- Relationship between income and spending
- Size and characteristics of different customer segments

## Applications
This segmentation can be used for:
- Targeted marketing strategies
- Customer service personalization
- Product recommendations
- Business strategy development 