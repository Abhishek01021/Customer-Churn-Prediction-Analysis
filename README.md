# Customer-Churn-Prediction-Analysis
Customer_Churn_Prediction_Analysis
📌 Project Overview  
This project simulates a corporate-grade, end-to-end churn analytics workflow, showcasing the ability to transform raw customer data into actionable retention strategies. The workflow is structured into four key phases:

✅ Data Transformation & Cleaning (SQL): Structured raw data (~6,400 rows) into relational tables, handled missing values, standardized attributes, and created analytical views (vw_ChurnData, vw_JoinData).
✅ Predictive Modeling & Exploratory Analysis (Python): Applied Random Forest classifier for churn prediction, performed feature importance analysis, and visualized churn distribution by tenure, contract type, and monthly charges.
✅ Visualization & Insights (Power BI): Built an interactive dashboard to profile churners, highlight at-risk customers, and uncover key drivers such as contract type, tenure, and payment method.
✅ Reporting & Presentation: Summarized findings in a structured report and presentation deck, providing actionable recommendations for customer retention.

⚙️ How to Use This Project

SQL (churn_prediction_sql.sql)  
• Create product_churn table and analytical views
• Run queries to analyze churn segments, tenure, and contract types
• Connect SQL database to Power BI

Python (churn_prediction_ml.ipynb)  
• Import and preprocess dataset
• Encode categorical variables and split train/test sets
• Train Random Forest model and evaluate performance
• Extract feature importance and visualize churn drivers

Power BI (churn_dashboard.pbix)  
• Build dashboards to visualize churn KPIs
• Explore churn distribution by tenure, contract, payment method, and geography
• Identify high-value customers at risk of churn

Reports & Presentations  
• Draft a structured report summarizing churn insights
• Create a presentation deck for stakeholder communication
