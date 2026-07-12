🚗 Maruti Suzuki On-Road Vehicle Price Prediction using Machine Learning
📌 Project Overview

This project develops an end-to-end Machine Learning solution to predict the On-Road Price of Maruti Suzuki vehicles using approximately 800,000+ sales records. The project focuses on data preprocessing, feature engineering, exploratory data analysis (EDA), model development, and business insights to support data-driven pricing decisions.

🎯 Business Problem

Accurately estimating the on-road price of a vehicle is essential for dealerships, pricing teams, and customers. Manual pricing is influenced by multiple factors such as vehicle model, fuel type, transmission, discounts, dealer location, and customer preferences.

Goal: Build a predictive model that accurately estimates vehicle prices while identifying the key factors affecting pricing.

📊 Dataset Information
Dataset Size: 797,687 Records
Domain: Automobile Sales
Target Variable: OnRoadPrice
Key Features
FuelType
Transmission
ExShowroomPrice
DiscountApplied
PaymentMode
CustomerType
SatisfactionScore
BookingToDeliveryDays
Model
VariantCode
Segment
DealerName
City
State
🛠 Tech Stack
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
📋 Project Workflow
1. Data Cleaning
Handled missing values
Removed hidden null values
Removed duplicate records
Corrected data types
Standardized categorical values
2. Exploratory Data Analysis (EDA)

Performed:

Univariate Analysis
Bivariate Analysis
Multivariate Analysis
Correlation Analysis
Skewness Analysis
Outlier Detection
Distribution Analysis
3. Feature Engineering

Created business features including:

PriceDifference
DiscountPercent
Year
Month
Quarter
DayOfWeek
4. Machine Learning Models

Models Compared

Linear Regression
Decision Tree Regressor
Random Forest Regressor
📈 Model Performance
Model	Test R²	MAPE
Linear Regression	0.45	30.38%
Decision Tree	0.9864	3.83%
Random Forest	0.9865	3.82%

Best Model: Random Forest Regressor

📊 Evaluation Metrics
R² Score
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
Mean Absolute Percentage Error (MAPE)
💡 Key Business Insights
Ex-Showroom Price is the strongest driver of vehicle pricing.
Vehicle Model and Base Variant significantly influence final prices.
Fuel Type and Transmission contribute to pricing differences.
Dealer Location impacts regional pricing variations.
Discount strategies affect the final customer price.
📌 Business Recommendations
Use the Random Forest model to improve dealership pricing accuracy.

🚀 Future Improvements
Hyperparameter Optimization
XGBoost implementation
Model Deployment using Flask/FastAPI
Real-time Price Prediction Web Application
Optimize discount strategies based on vehicle segments.
Monitor dealer-wise pricing differences for consistency.
Support pricing decisions using predictive analytics instead of manual estimation.

📌 Author

Santosh Gautam

Aspiring Data Analyst | Python | SQL | Power BI | Machine Learning

If you found this project helpful, feel free to ⭐ the repository.

📧 Email: gautam21santosh@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/gautam21santosh

💻 GitHub: https://github.com/gautam21santosh-byte
