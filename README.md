# Netflix_Engagement_Churn_Analysis
This project focuses on analyzing customer churn for Netflix by combining SPSS for statistical modeling and Power BI for data visualization. The objective was to predict and analyze churn using engagement data such as watch time, satisfaction scores, and subscription types, while also building an interactive dashboard to monitor key churn KPIs.

The project follows a structured data analytics pipeline: Data Preparation → Statistical Analysis → Predictive Modeling → Visualization → Insights.

## Objectives
- Predict customer churn using statistical modeling
- Identify key factors affecting churn behavior
- Segment high-risk customers for targeted retention
- Visualize churn patterns through dashboards

# 🛠️ Tools Used

### SPSS (Statistical Package for Social Sciences)
- Logistic Regression for **churn prediction**  
- ANOVA & Descriptive Stats for engagement insights  
- Crosstabs for categorical analysis  

### Power BI
- Built dashboards tracking **15+ KPIs**  
- Used **DAX & Power Query** for modeling  
- Visualized churn trends by demographics, subscription type, and engagement metrics

# 📂 Dataset Description 
3,500 customer records containing features such as Age, Daily Watch Time, Customer Satisfaction Score, Subscription Plan, Payment History, and Churn Status.

# 🔎 Methodology
### Step 1. Data Preparation  
- Imported dataset into SPSS  
- Checked missing values & data types  
- Cleaned and formatted for analysis  

### Step 2. Descriptive Analysis  
- Churn rate calculation  
- Mean watch time by churn status  
- Churn distribution across regions & subscription types  

### Step 3. Bivariate Analysis  
- **Crosstabs**: Churn vs Subscription Plan, Device Used  
- **ANOVA / t-test**: Watch time & Satisfaction vs Churn  

### Step 4. Predictive Modeling  
- **Performed Binary Logistic Regression**  
  - Dependent Variable: Churn  
  - Independent Variables: Age, Watch Time, Satisfaction, Payment History  
- Achieved **85% model accuracy**  

### Step 5. High-Risk Customers Segmentation  
- Classified customers with **probability > 60%** as high-risk  
- Created new variable (`High_Risk`) in SPSS  

### Step 6. Dashboard Development  
- KPIs: Total Customers, Churn Rate, Avg. Watch Time, High-Risk %  
- Visuals: Pie Charts (Churn %), Bar Graphs (Churn by Plan), Boxplots (Engagement)

# 📊 Dashboard Preview
<img width="901" height="504" alt="image" src="https://github.com/user-attachments/assets/d8908912-d38d-4de7-b425-63f9bc1ff830" />

# 📈 Key Insights
1) Customers with Basic plans and delayed payments showed higher churn probability.
2) Lower satisfaction scores (<5) strongly correlated with churn.
3) Young customers (<30 years) with shorter tenure were more likely to leave.
4) Identified 20% of customers as high-risk churners.

# Final Outcome
The project achieved 85% model accuracy in predicting churn using SPSS, enabling reliable identification of high-risk customers. The Power BI dashboard provided real-time monitoring of key churn KPIs, offering a clear view of customer engagement trends.

Suggestion: Netflix should implement retention strategies such as loyalty offers, targeted promotions, and timely payment reminders to strengthen customer relationships and reduce churn.
