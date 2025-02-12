# shanghai-ranking-analysis
Analysis and visualization of the 2024 Shanghai Ranking of Universities, as well as visualizing the correlation between university metrics via heatmap
# Shanghai Ranking Analysis 2024

This project focuses on the analysis and visualization of the **Shanghai Ranking of Universities 2024**. It leverages data analysis and visualization techniques to explore university performance and correlations across various metrics.

## Overview
The goal of this project is to clean, process, and visualize the data from the 2024 Shanghai Ranking. It includes the following key steps:

- **Data Cleaning & Preprocessing**: The dataset contains university rankings and various associated metrics. Missing or erroneous values were handled by using imputation and conversion techniques.
- **Top 10 University Visualization**: A horizontal bar chart is generated to visualize the top 10 universities based on their global rank.
- **Correlation Analysis**: A heatmap is produced to visualize the correlation between different university metrics, helping to identify patterns and relationships in the data.
  
## Key Features:
- **Data Cleaning**: Conversion of non-numeric values to integers and imputation of missing values.
- **Visualization**: 
  - Bar chart showing the top 10 universities based on rank.
  - Correlation heatmap to understand relationships between university metrics.
- **Pandas & Matplotlib**: Utilizes popular Python libraries such as Pandas for data manipulation and Matplotlib/Seaborn for visualizations.

## Requirements:
To run this project, you’ll need the following Python libraries:
- `pandas`
- `matplotlib`
- `seaborn`

You can install the required libraries using `pip`:
```bash
pip install pandas matplotlib seaborn
