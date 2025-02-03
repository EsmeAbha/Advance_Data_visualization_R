### Description:
This R code provides a comprehensive analysis of the hepatitis dataset using various visualization techniques. It starts by reading the dataset and exploring relationships between numerical variables through scatterplot matrices and correlation analysis. Key visualizations include hexagonal binning, bubble charts, mosaic plots, heatmaps, box plots, and density plots, highlighting patterns in variables like Age, ALT, AST, Albumin (ALB), Bilirubin (BIL), and Cholesterol (CHOL). Other advanced visualizations like 3D scatter plots, ridge plots, alluvial plots, violin plots, slope plots, and ECDF plots are used to explore distributions and relationships between categories and numerical features. Additionally, pie charts and contour plots provide insights into categorical data and joint distributions.

### README:
This project analyzes the hepatitis dataset using R, focusing on visualizations and correlation analysis of different variables to understand their relationships and distributions. The main steps include:

1. **Exploratory Data Analysis**: Using scatterplot matrices and pairwise correlations to investigate relationships between numerical variables.
2. **Hexagonal Binning**: A plot to examine the joint distribution of Age and Albumin (ALB).
3. **Correlation Matrix & Heatmap**: The correlations between numerical features are visualized in a correlation matrix and heatmap.
4. **Bubble Charts**: Visualizing the relationship between Age, ALB, and Bilirubin (BIL).
5. **Categorical Visualizations**: Using mosaic plots, pie charts, and alluvial plots to explore categorical relationships.
6. **Advanced Visualizations**: Ridge plots, 3D scatter plots, violin plots, and contour plots for understanding distributions and relationships.
7. **Additional Plots**: ECDF and slope plots to study cumulative and linear relationships between variables like ALT, AST, ALP, and CHOL.

### How to Run:
1. Ensure that the `hepatitis_data.csv` file is available in the specified directory (`E:/Desktop/OneDrive/Documents/IDS/ds/Hepatitis data/hepatitis/`).
2. Install necessary libraries like `ggplot2`, `hexbin`, `corrplot`, `plotly`, `ggalluvial`, `ggthemes`, and `ggridges` for visualization.
3. Run the R script to generate various plots and analyses of the hepatitis data.

This analysis is designed to uncover important patterns and relationships in the dataset, aiding in better understanding of hepatitis-related factors.
