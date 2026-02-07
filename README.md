# youtube-channel-analytics
Developed a machine learning–driven analysis to study and predict YouTube revenue and engagement using per-video, per-day analytics data. Applied feature engineering and regression models to identify key monetization drivers, and used Power BI to visualize and validate insights around views, RPM, engagement, and revenue concentration.
# Machine Learning Analysis of YouTube Revenue & Engagement

## Objective
The primary objective of this project is to apply machine learning techniques to analyze
and predict YouTube video revenue and engagement patterns. Power BI is used as a
supporting visualization layer to validate and communicate model insights.

## Dataset
- Source: YouTube Analytics export
- Granularity: Per-video, per-day
- Records: 364
- Target Variables:
  - Estimated Revenue (USD)
  - Engagement Rate

## Machine Learning Workflow
1. Exploratory Data Analysis (EDA)
2. Feature Engineering (RPM, engagement metrics, temporal features)
3. Model Training (Regression models)
4. Model Evaluation (RMSE, R²)
5. Insight Extraction

## Models Used
- Linear Regression
- Random Forest Regressor
- (Optional) XGBoost

## Key Insights
- Revenue is driven more by RPM and engagement than raw views.
- High view counts do not guarantee higher revenue.
- Temporal features significantly impact monetization efficiency.

## Visualization
Power BI was used to visualize trends, revenue concentration, and engagement efficiency,
supporting the findings from the machine learning models.

## Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn)
- Power BI
- DAX
