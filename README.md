# Netflix-Stock-Prediction.
My first data science project: Predicting Netflix Open prices using Linear Regression &amp; correlation analysis.
This project successfully applied Linear Regression to analyze the relationship between Close and Open stock prices. By training the model on the first 500 rows of data and testing it on the last 100 rows, we were able to measure both accuracy and consistency.

The regression equation derived from the dataset shows that the Open price can be estimated directly from the Close price with a linear relationship. The performance metrics (R² and RMSE) demonstrated that the model fits the training data well and is reasonably accurate when tested on unseen data.

The correlation analysis between the predicted values and the actual values for the last 100 rows revealed a moderate-to-strong positive correlation, confirming that the model captures the underlying trend in the dataset. The visualizations (line chart and scatter plot) further supported these findings by showing the alignment between predicted and actual values.

🔹 Key Insights:

1. Close and Open prices are positively correlated – meaning that changes in the closing price can help predict the opening price.


2. The R² and RMSE values indicate a reliable but not perfect prediction model.


3. The scatter plot showed that most predicted values lie close to the ideal fit line (y = x), validating the model’s performance.


4. For real-world forecasting, more advanced models (such as LSTM, Random Forest, or XGBoost) may further improve accuracy compared to simple linear regression.



✅ Final Remark:

This project demonstrates that Linear Regression is a simple yet powerful tool for analyzing stock price relationships. While it may not capture all market complexities, it provides a solid foundation for predictive modeling in financial data analysis.
