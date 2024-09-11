# Chennai-House-Price-Prediction
Chennai House Price Prediction using machine learning with linear regression in Python. Performed EDA to identify outliers using Isolation Forest, and predicted house prices. Integrated Python script in Power BI to predict and visualize prices, with DAX operations for enhanced insights and dashboard visualization.


# Exploratory Data Analysis


![EDA](https://github.com/user-attachments/assets/3050dd18-ce9a-4490-a02a-a2beede8a011)

Exploratory data analysis (EDA) is crucial for understanding the data. We will analyze the distribution of features, and check for any outliers or missing values.

1. Outlier Detection:

   Outliers are data points that differ significantly from other observations. They can skew analysis and may indicate variability, errors, or interesting behavior in data.

2. What Is Isolation Forest ?

    Isolation Forest is an anomaly detection algorithm that identifies outliers by isolating data points. It works by randomly selecting a feature and then splitting the data, with the idea that outliers are easier to isolate.

3. Why Is Isolation Forest ?

    Isolation Forest is efficient for detecting anomalies in large datasets because it is faster and less computationally expensive compared to other methods, making it ideal for identifying outliers in complex datasets like house prices.

# Implementing Linear Regression in Python


We use Python's scikit-learn library to implement linear regression. First, we split the data into training and testing sets. The training set is used to train the model, while the testing set is used to evaluate its performance.


1. Data Preparation

   The data is cleaned and preprocessed, including handling missing values and transforming features.

2. Model Training

   We train the linear regression model using the prepared training data. This involves finding the coefficients that minimize the error between predicted and actual prices.

3. Model Evaluation

   The trained model is then evaluated using the testing data to assess its performance on unseen data. Common metrics include R-squared and mean squared error.

# Predict House Price in Power BI

I Implemented a Power BI's Python script integration to implement a linear regression model for predicting house prices. Using Python within Power BI, I built and trained the linear regression model on historical house pricing data, with the aim of forecasting future prices based on relevant features such as location, size, and number of rooms. The integration allowed me to run the Python script directly in Power BI, seamlessly blending the predictive power of Python with Power BI's visualization capabilities.


![python script of powerbi](https://github.com/user-attachments/assets/2add2a98-1053-4b9e-a8a1-cb105c3e126f)


Once the model predicted house prices, I visualized the results alongside other key columns (e.g., house size, location, and market trends) in a Power BI dashboard. This provided a clear, data-driven representation of how different variables impacted price predictions, making it easier to interpret the results.
