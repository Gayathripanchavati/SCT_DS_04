Accident Dataset Analysis

📁 Dataset
Source: [Open Data Repository / Kaggle Accident Dataset]
File Used: accidents.csv
This dataset contains records of road accidents, including location, time, weather, road conditions, and severity. The goal is to analyze patterns, identify high-risk factors, and provide actionable insights for road safety.

🎯 Project Objective
Analyze accident data to identify high-risk locations, contributing factors, and severity patterns, and build predictive models to classify accident severity.

⚙ Steps Followed

Data Preparation

Loaded dataset into Google Colab.

Handled missing values and duplicates.

Standardized column formats and cleaned inconsistent entries.

Exploratory Data Analysis (EDA)

Examined accident distribution by time, location, weather, and severity.

Visualized trends using heatmaps, bar plots, and scatter plots.

Identified patterns in high-risk areas and conditions.

Data Preprocessing

Encoded categorical variables for modeling.

Filtered features relevant to accident prediction.

Split dataset into features (X) and target (y).

Modeling

Built Logistic Regression model to predict accident severity.

Evaluated model performance using accuracy metrics and ROC curves.

Visualization

Created interactive maps and plots using Plotly to highlight hotspots.

Analyzed correlations between features and accident outcomes.

📊 Key Results & Insights

Peak accidents occur during rush hours.

Weather conditions (rain, fog) significantly increase accident risk.

Poor road conditions (low lighting, potholes) contribute to higher severity.

Accident severity prediction model achieved ~82% accuracy.

🔧 Tools & Libraries Used
Python · Pandas · NumPy · Matplotlib · Seaborn · Plotly · Scikit-learn · Google Colab

🚀 Future Work

Forecast accident trends using time-series analysis.

Integrate real-time traffic and weather data for predictive modeling.

Build a dashboard (Streamlit / Power BI) for policymakers and safety authorities.

📌 How to Run
Install dependencies:

pip install pandas numpy matplotlib seaborn plotly scikit-learn


Run in Colab:


Or locally:

python accident_analysis.py


✅ Repository Link: https://github.com/Gayathripanchavati/SCT_DS_04.git

#SkillCraftTechnology #AccidentDataset #DataScience #RoadSafety #EDA #MachineLearning #Python #DataVisualization
