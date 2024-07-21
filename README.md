# OTT-Churn
### Problem Statement
The objective is to analyze customer churn data from a leading subscription-based streaming service. This industry giant offers a vast library of movies, TV shows, and original content. Understanding why customers discontinue their subscriptions is crucial for optimizing the user experience, reducing churn, and maximizing customer lifetime value.

### Objective
1. **Data Exploration and Analysis**: Conduct a thorough exploratory data analysis (EDA) to understand the distribution and relationships of various features related to customer subscriptions.
2. **Predictive Modeling**: Develop a machine learning model to predict customer churn, enabling proactive retention strategies.

### Project Highlights
- **Data Collection**: The dataset includes various features such as customer demographics, subscription details, payment methods, viewing behavior, and churn status.
- **Data Cleaning**: Handle missing values, outliers, and data inconsistencies to ensure the quality of the analysis and model performance.
- **Exploratory Data Analysis (EDA)**: Visualize and summarize the key characteristics of the data to identify patterns and insights.
- **Feature Engineering**: Create new features from the existing ones to improve the predictive power of the model.
- **Model Selection and Evaluation**: Train and evaluate multiple machine learning models to select the best one based on performance metrics like accuracy, precision, recall, and F1-score.

### Project Description
1. **Data Overview**:
   - **Features**:
     - **CustomerID**: Unique identifier for each customer
     - **SubscriptionType**: Type of subscription plan chosen by the customer
     - **PaymentMethod**: Method used for payment
     - **PaperlessBilling**: Whether the customer uses paperless billing
     - **ContentType**: Type of content accessed by the customer
     - **MultiDeviceAccess**: Whether the customer has access on multiple devices
     - **DeviceRegistered**: Device registered by the customer
     - **GenrePreference**: Genre preference of the customer
     - **Gender**: Gender of the customer
     - **ParentalControl**: Whether parental control is enabled
     - **SubtitlesEnabled**: Whether subtitles are enabled
     - **AccountAge**: Age of the customer's subscription account (in months)
     - **MonthlyCharges**: Monthly subscription charges
     - **TotalCharges**: Total charges incurred by the customer
     - **ViewingHoursPerWeek**: Average number of viewing hours per week
     - **SupportTicketsPerMonth**: Number of customer support tickets raised per month
     - **AverageViewingDuration**: Average duration of each viewing session
     - **ContentDownloadsPerMonth**: Number of content downloads per month
     - **UserRating**: Customer satisfaction rating (1 to 5)
     - **WatchlistSize**: Size of the customer's content watchlist
     - **Churn**: Situation of customer churn or not (target variable)

2. **EDA Key Insights**:
   - **Demographics**: Analyzed the distribution of customer demographics such as gender, age, and genre preferences.
   - **Subscription Details**: Explored the impact of subscription type, payment method, and monthly charges on churn.
   - **Viewing Behavior**: Investigated how viewing hours, content type, and device access correlate with customer churn.

3. **Predictive Modeling**:
   - **Data Preprocessing**: Applied techniques such as normalization, encoding categorical variables, and splitting the data into training and testing sets.
   - **Model Training**: Evaluated models including Logistic Regression, Decision Trees, Random Forests, and Gradient Boosting.
   - **Model Evaluation**: Assessed model performance using metrics such as confusion matrix, ROC-AUC, and cross-validation scores.

### Conclusion
By analyzing the customer churn data and developing a predictive model, we can better understand the factors contributing to churn and implement strategies to enhance customer retention. The insights gained from this project will help the streaming service provider to optimize their offerings, improve customer satisfaction, and ultimately reduce churn rates.
