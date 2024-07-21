## Problem Statement
The objective is to analyze customer churn data from a leading subscription-based streaming service. This industry giant offers a vast library of movies, TV shows, and original content. Understanding why customers discontinue their subscriptions is crucial for optimizing the user experience, reducing churn, and maximizing customer lifetime value.

## Objective
### Data Exploration and Analysis:
Conduct a thorough exploratory data analysis (EDA) to understand the distribution and relationships of various features related to customer subscriptions.
### Predictive Modeling:
Develop a machine learning model to predict customer churn, enabling proactive retention strategies.
## Project Highlights
### Data Collection:
The dataset includes various features such as customer demographics, subscription details, payment methods, viewing behavior, and churn status.
### Data Cleaning:
Handle missing values, outliers, and data inconsistencies to ensure the quality of the analysis and model performance.
### Exploratory Data Analysis (EDA):
Visualize and summarize the key characteristics of the data to identify patterns and insights.
### Feature Engineering: 
Create new features from the existing ones to improve the predictive power of the model.
### Model Selection and Evaluation:
Train and evaluate multiple machine learning models to select the best one based on performance metrics like accuracy, precision, recall, and F1-score.
## Project Description
### Data Overview:

Features:
- CustomerID: Unique identifier for each customer
- SubscriptionType: Type of subscription plan chosen by the customer
- PaymentMethod: Method used for payment
- PaperlessBilling: Whether the customer uses paperless billing
- ContentType: Type of content accessed by the customer
- MultiDeviceAccess: Whether the customer has access on multiple devices
- DeviceRegistered: Device registered by the customer
- GenrePreference: Genre preference of the customer
- Gender: Gender of the customer
- ParentalControl: Whether parental control is enabled
- SubtitlesEnabled: Whether subtitles are enabled
- AccountAge: Age of the customer's subscription account (in months)
- MonthlyCharges: Monthly subscription charges
- TotalCharges: Total charges incurred by the customer
- ViewingHoursPerWeek: Average number of viewing hours per week
- SupportTicketsPerMonth: Number of customer support tickets raised per month
- AverageViewingDuration: Average duration of each viewing session
- ContentDownloadsPerMonth: Number of content downloads per month
- UserRating: Customer satisfaction rating (1 to 5)
- WatchlistSize: Size of the customer's content watchlist
- Churn: Situation of customer churn or not (target variable)
### EDA Key Insights:

- Demographics: Analyzed the distribution of customer demographics such as gender, age, and genre preferences.
- Subscription Details: Explored the impact of subscription type, payment method, and monthly charges on churn.
- Viewing Behavior: Investigated how viewing hours, content type, and device access correlate with customer churn.
### Predictive Modeling:

- Data Preprocessing: Applied techniques such as normalization, encoding categorical variables, and splitting the data into training and testing sets.
- Model Training: Evaluated models including Logistic Regression, Decision Trees, Random Forests, and Gradient Boosting.
- Model Evaluation: Assessed model performance using metrics such as confusion matrix, ROC-AUC, and cross-validation scores.
## Conclusion
### Paperless Billing:

Customers who are not on paperless billing tend to have lower churn rates (correlation of approximately -0.98).
However, customers on paperless billing still exhibit a slightly higher churn rate (correlation of around -0.91).
#### Insight:
Paperless billing significantly impacts churn behavior, and customers who prefer paperless billing are more likely to churn.
### Content Type:

Movie content has the lowest churn rate, followed by TV shows and both.
Users who subscribe to both movie and TV show content have a higher churn rate.
#### Insight:
Consider tailoring content recommendations based on user preferences to reduce churn.
### Genre Preferences:

Comedy content has the highest churn rate, while genres like Sci-Fi, drama, fantasy, and action have lower churn rates.
Most users prefer comedy, followed by fantasy, drama, action, and Sci-Fi.
#### Insight:
Personalizing content offerings based on genre preferences can improve retention.
### Parental Control and Subtitles:

High churn occurs among users with no parental control and no subtitle enabled.
Many users have both parental control and subtitles enabled.
#### Insight:
Enhancing parental control features and ensuring subtitle availability may positively impact retention.
### Correlations:

#### Negative correlations:
AccountAge, Viewinghoursperweek, Averageviewduration, and Contentdownloadpermonth are associated with lower churn rates.
#### Positive correlations:
Supportticketpermonth, userrating, and watchlistsize are associated with higher churn rates.
#### Insight: 
These correlations can guide targeted strategies to reduce churn (e.g., improving customer support or enhancing content recommendations).
