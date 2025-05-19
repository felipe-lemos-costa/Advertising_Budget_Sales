# Advertising_Budget_Sales
![advertising_logo](images/advertising_logo.jpg)

# Summary
This project analyzes the relationship between investments in different advertising channels (TV, radio, and newspapers) and their impact on company sales. The goal is to understand how each channel contributes to sales performance, using advertising budgets as explanatory variables and sales volume as the target variable.

# Key Insights
1. Analyzing the Sales histogram, we observed a slightly higher concentration to the left, with a slight tail to the right:
![Sales Histogram](https://github.com/felipe-lemos-costa/Advertising_Budget_Sales/raw/main/images/1_sales_histogram.jpg)

2. The correlation matrix revealed a strong positive correlation between Sales and TV Ad Budget, indicating that higher investments in TV ads are associated with higher sales. On the other hand, the correlation with Radio Ad Budget showed a moderate positive correlation, while the correlation with Newspaper Ad Budget exhibited a weak positive correlation:
![Correlation Matrix](images/2_correlation_matrix.png)

3. The line chart displays the correlation between the variables, ordered from the most strongly correlated (TV Ad Budget) to the least correlated(Radio Ad Budget).
![Line Plot](images/3_line_plot.png)

4. In the scatter plots, the most notable feature is the strong positive correlation between Sales and TV Ad Budget. The plots of Sales compared to Radio Ad Budget showed greater dispersion, while the plots of Sales versus Newspaper Ad Budget displayed even greater dispersion.
![Scatter Plots](images/4_scatter_plots.png)

5. The analysis of the boxplot visually revealed the presence of two outliers in the Newspaper Ad Budget. These outliers could be explained by special events or campaigns where a large investment in ads was made for specific occasions.
![Box Plot](images/5_box_plot.png)

6. Three Machine Learning models were tested to predict sales: KNN (K-Nearest Neighbors), Decision Tree, and Linear Regression. The evaluation of the models was performed using the R² coefficient of determination and Mean Squared Error (MSE), through cross-validation. Although very similar to KNN, the results indicated that the Decision Tree model showed the best performance with an R² value of 94,6% and an MSE of 1.58, making it the most suitable option for the analyzed dataset, as the KNN model with an R² of 96,1% and an MSE of 1.78 carries a higher risk of overfitting.
![MSE Comparison](images/5_mse_comparison.png)



