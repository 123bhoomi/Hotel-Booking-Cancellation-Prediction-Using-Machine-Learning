# Hotel-Booking-Cancellation-Prediction-Using-Machine-Learning
Built ML models on hotel booking data to predict cancellations, applying preprocessing, feature engineering, and advanced visualizations, with evaluation across multiple algorithms to identify the best-performing model.

Task 1: Data Cleaning And Preprocessing:
-Missing Data Handling: Identify and handle missing values in columns like children, country, and agent. Decide whether to impute missing values or remove rows with missing data.
-Outlier Detection: Check for anomalies in columns like adr (extreme values) and lead_time (very high values may need handling).
-Data Type Conversion: Ensure all data columns have the correct data types.

Task 2: Feature Engineering:
-Feature Scaling: Apply scaling techniques to numerical features.
-Categorical Grouping: Group bookings into three categories based on lead _time:
• Short: lead_time < 30 days
• Medium: 30 days < lead _time < 90 days
• Large: 90 days > lead _time

Task 3: Complex Calculations And Advanced Functions:
-Running Total Analysis: Create a running total chart to show cumulative booking cancellations over time.
-Weighted Booking Score: Compute a weighted cancellation rate by considering both previous_cancellations and previous_bookings_not_canceled.
-Dynamic Rank Calculation: Use ranking techniques to dynamically rank hotels based on their cancellation rate.

Task 4: Advanced Filtering And Parameterized Visualizations:
-Dynamic Market Segment Analysis: Create a query that allows users to filter bookings by market segment dynamically.
-Find High-Risk Customers: Retrieve a list of customers who had multiple cancellations in the past.
-Most Frequent Guests: Identify the most frequent guests based on repeated bookings.
-Seasonal Booking Trends: Identify peak booking months and trends across different hotels.

Task 5: Joins And Multi-Table Queries:
-Hotel-Specific Cancellation Rate: Find the total number of cancellations per hotel type.
-Countries With High Cancellation Rates: List all countries from which guests have a high tendency to cancel bookings.

Task 6: Model Building:
-Split the Dataset: Split the dataset into training and testing sets (e.g., 80% training, 20% testing).
-Experiment with models, mainly logistic regression, decision tree, random forest, gradient boosting machines, support vector machines.
-Hyperparameter Tuning: Use Grid Search or Random Search to optimize hyperparameters.

Task 7: Model Testing:
-Evaluate performance using accuracy, precision, recall, F1-score and AUC-ROC.
-Use cross-validation techniques.
-Compare model performance and determine the best one based on evaluation metrics.
