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


# Visualize Predicted House Price in Power BI

This Power BI dashboard is a powerful tool for visualizing predicted house prices and comparing them across various dimensions such as location, BHK count, sale condition, and more. By combining Python’s linear regression model for price prediction with Power BI’s interactive visualizations and DAX operations, you have created an intuitive and insightful platform for real estate analysis. This dashboard would be valuable for real estate agents, property investors, or anyone looking to understand house price trends based on historical data and predictions.


![House Price Prediction Power Bi Dashboard](https://github.com/user-attachments/assets/63a5fa48-4753-4728-80d8-a1de122c11cf)


1. KPI Cards: Display key metrics, including the total number of houses, the predicted total house price, and the potential commission.

2. Actual Price vs. Predicted Price (Scatter Plot): Shows the relationship between actual and predicted house prices, highlighting the model’s accuracy.

3. Predicted Price by Year Built (Line Chart): Illustrates the trend of predicted house prices based on the year houses were built.

4. Predicted Price by Total BHK and Location (Bar Chart): Compares predicted house prices across different BHK configurations and locations.

5. Predicted Price by Sale Condition (Pie Chart): Breaks down predicted house prices according to various sale conditions, such as normal, abnormal, or family sales.


![House Price Prediction Power Bi Dashboard 2](https://github.com/user-attachments/assets/ad78fc4c-2279-402e-95e0-460a03a77830)


1. KPI Card (Actual vs Predicted Price by Parking Facility): Shows the total predicted price of houses considering parking facilities, compared to the target goal.

2. Total Houses by Location (Donut Chart): Displays the distribution of the total number of houses across various locations.

3. sq.ft and Total Commission by BHK (Bar and Line Chart): Compares the commission earned and the square footage for each BHK type.

4. sq.ft and Total BHK by Location (Line Chart): Highlights the total square footage and number of BHKs across different locations.

# Analyzing the Prediction Results

I analyze the prediction results to identify patterns and trends. This includes investigating the impact of different features on price predictions and evaluating the model's strengths and weaknesses.


![image](https://github.com/user-attachments/assets/d75f3730-1a55-4542-89f1-7505506b591a)

1. Accuracy

     The model's accuracy is assessed by analyzing its performance metrics and 
 visually inspecting the predicted vs. actual price relationships.

2. Feature Importance

     I examine the feature coefficients to determine which features have the most significant impact on house prices and how they contribute to the overall predictions.

3. Outlier Impact

     The influence of outliers on the model's predictions is investigated to understand how they affect the overall accuracy and make adjustments if necessary.



#  Conclusion and Key Takeaways

The house price prediction project aimed to predict property prices in Chennai using machine learning techniques and data analysis methodologies. By implementing linear regression in Python and conducting extensive exploratory data analysis (EDA), the project successfully identified key factors influencing house prices and offered predictive insights. Additionally, the integration of Power BI allowed for enhanced visualization of predictions, ensuring a more user-friendly representation of the data.

The project followed a structured approach starting with data pre-processing. This involved handling missing values, encoding categorical variables, and normalizing the dataset to ensure optimal model performance. A crucial aspect of this phase was the identification and treatment of outliers. Utilizing the EDA method, outliers were detected using techniques such as the isolation forest model. This model proved efficient in flagging anomalous data points that could negatively affect the performance of the predictive model. By visualizing these outliers, the data could be cleaned effectively, allowing for a more robust prediction model.

Once the data was prepared, the next phase involved building and training the machine learning model. A linear regression model was selected due to its simplicity and effectiveness in predicting continuous variables like house prices. By training the model on historical data, it could learn the relationships between various features (such as the size of the house, location, number of rooms, etc.) and the target variable, which was the house price. The model was evaluated based on common performance metrics like R-squared and Mean Absolute Error (MAE), ensuring its accuracy and reliability.

The second part of the project involved leveraging Power BI to provide a powerful visualization layer. Here, the Python script integration in Power BI was used to implement the same linear regression model for predictions. The seamless integration of Python and Power BI offered the dual advantage of performing advanced analytics and displaying the results in an intuitive and interactive manner. In Power BI, the predicted house prices, along with other relevant columns like location, house size, and number of rooms, were visualized to give a clear understanding of the pricing trends. Additionally, DAX (Data Analysis Expressions) operations were used to further enhance the dashboard, allowing for more dynamic and insightful interactions with the data.


In summary, the project achieved its objectives by successfully predicting house prices using a combination of machine learning and visualization techniques. The linear regression model provided accurate predictions, while the Power BI dashboard made the results accessible and understandable to a broader audience. The use of EDA and outlier detection methods ensured data quality, and the integration of Python scripts in Power BI demonstrated the power of combining data science with business intelligence tools. This project has significant real-world applications, such as helping real estate companies and potential buyers make informed decisions by predicting house prices based on key features.



