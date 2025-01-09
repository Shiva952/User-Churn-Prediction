# User Churn Prediction 
 The objective of this project is to build the ML model to predict the users who are most likely to churn. And to provide the insights behind the churn and focusing on actionable business takeaways. 
## Dataset: 
1. event_time: Datetime of the event (e.g., 2020-12-01 09:00:00) 
2. event_type: Type of the event, one of view, cart, or purchase 
3. product_id: Identifier of the product 
4. category_id: Identifier of the product’s category 
5. category_code: Human-readable category code (if available) 
6. brand: Brand of the product 
7. price: Price of the product (numerical) 
8. user_id: Identifier of the user who performed the event 
9. user_session: Identifier of the user’s session 
## Methodology: 
### 1. Data Pre-processing: 
o After loading dataset, the first step is Data pre-processing. In the data we have 
some duplicates and missing values. So, in this step I have transformed the data 
and update the missing and duplicated records. 
### 2. EDA (Exploratory Data Analysis): 
o In this step I have analyzed the data, and created some visualizations showing 
Event type distributions, Checking for Brand popularity, User level summary. 
### 3. Churn Definitions: 
o In this step I have created the dataframe showing which user is most likely to 
churn. 
### 4. Feature Engineering: 
o Next step involves feature engineering where I have created some additional 
feature for user churn prediction. 
o I have grouped the users based on their records of views, carts, purchases and I 
have created the new features like view to cart ratio and cart to purchase ratio. 
o This new features describe about how many users are viewing, adding them to 
cart and purchasing the products. 
### 5. Model Training: 
o Next step is implementing the ML algorithm. I have split the data into train and 
test data and I have used Random forest classifier algorithm. I have used RFC to 
avoid the overfitting of the model. 
### 6. Feature Importance: 
o I have built a visualization chart for feature importance showing which feature 
is more important for predicting the user churn. 
## Business Recommendations: 
I have given following recommendations for user retention for the e-commerce platform. 
• Target users with high view-to-cart ratios but low cart-to-purchase ratios with person
 alized offers. 
• Encourage repeat purchases with loyalty rewards for frequent buyers. 
• Re-engage churned users with email campaigns or discounts.
