# Melbourne Housing Business Analytics

This project leverages business analytics and machine learning techniques to analyze the **Melbourne Housing Dataset** and predict property prices. By exploring key features influencing property prices and utilizing regression models, the project provides actionable insights for informed investment decisions and improved business performance for real estate consulting firms. It is structured as a **two-part project**, with each part building upon the previous to deliver a comprehensive analysis and actionable business insights.

## Project Overview
### **Part 1: Exploration of Business Analysis Tasks**
- Focused on data cleaning, exploratory data analysis (EDA), and understanding the dataset.
- Proposed and justified potential **Business Analysis Tasks**, including:
1. **Association Rule Mining:**  
     - Identifies relationships between features (e.g., properties with more bedrooms often have larger land sizes and higher prices).  
     - Enables targeted marketing strategies and personalized property recommendations.
2. **Classification:**  
     - Predicts labels such as whether a property will be sold swiftly based on features like property type, postcode, and sales method.  
     - Supports better marketing, inventory management, and client targeting.  
3. **Regression:**  
     - Predicts property prices based on features such as rooms, distance from CBD, land size, and building area.  
     - Reveals key features influencing property prices and provides actionable insights for investment decisions. 
- Provided detailed justifications for each potential task, evaluating their feasibility and business impact.

### **Part 2: Implementation of Regression Analysis**
- Built upon the foundation of Part 1 by selecting **Regression Analysis** as the primary task to predict property prices.  
- Focused on **feature engineering, model development, and evaluation**, delivering actionable insights for property investment decisions.  
- Implemented and compared multiple regression models, including **Linear Regression, Random Forest Regression, and Gradient Boosting Regression (GBR)**.
- Delivered refined business recommendations based on predictive modeling outcomes and feature importance analysis.

## Key Features
- Comprehensive **data cleaning and preprocessing** to address null values, outliers, and data inconsistencies.
- Conducted **Exploratory Data Analysis (EDA)** to uncover property trends, key factors influencing prices, and correlations.
- Built regression models (**Linear Regression, Random Forest Regression, and Gradient Boosting Regression**) to predict property prices.
- **Evaluation Metrics Used:**
  - Root Mean Squared Error (RMSE)
  - Mean Absolute Error (MAE)
  - R² Score
- Delivered actionable business recommendations for investment strategies, resource allocation, and operational efficiency.

## Dataset
- **Source:** Melbourne Housing Dataset
- **Features:** 22 attributes including property details (Rooms, Bathroom, Land Size), location (Latitude, Longitude, Region Name), and market metrics (Price, Method, Date).
- Target feature: **Price**

## Technologies Used
- **Programming Language:** Python
- **Key Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
