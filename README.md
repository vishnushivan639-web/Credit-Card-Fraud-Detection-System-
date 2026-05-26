🛡️ Credit Card Fraud Detection System

Detecting Fraudulent Transactions Using Data Analytics and Machine Learning

📌 Overview

This project focuses on analyzing credit card transaction data to identify fraudulent and suspicious transactions using:

Exploratory Data Analysis (EDA)
Linear Regression
Interactive Dashboard Visualization

The system is designed with a structured and scalable workflow that helps financial institutions:

Detect unusual transaction behavior
Reduce fraud-related financial losses
Improve fraud monitoring systems
Support better risk management strategies
🚀 Project Workflow

The complete workflow includes:

Data collection
Data preprocessing and cleaning
Exploratory Data Analysis (EDA)
Fraud behavior analysis
Risk analysis
Linear Regression model building
Dashboard visualization using Plotly
Model evaluation and insights generation
🎯 Main Goal

The main objective of this project is to:

 Identify fraudulent transaction patterns
 Analyze transaction behavior
 Detect suspicious activities
 Support fraud prevention strategies
 Improve financial security systems

📂 Dataset
Dataset Source

Kaggle

Dataset Name

Credit Card Fraud Detection Dataset

📖 Dataset Description

The dataset contains real-world credit card transaction information collected from financial transaction systems.

The dataset includes:

Transaction time
Transaction amount
Anonymized transaction features
Fraud labels
📌 Selected Features
Feature Name	Description
Time	Time elapsed between transactions
Amount	Transaction amount
V1 – V28	Anonymized transaction features
Class	Target variable (0 = Normal, 1 = Fraud)
🗑️ Removed Columns

The following were removed to simplify analysis:

Duplicate transaction records
Sparse columns
Unnecessary identifiers
Irrelevant metadata
🎯 Objectives

The project aims to:

Analyze transaction behavior
Identify fraud influencing factors
Perform data cleaning and preprocessing
Conduct statistical and relationship analysis
Build a Linear Regression model
Evaluate prediction performance
Create interactive dashboards
Support fraud risk management
⭐ Project Highlights
🧹 1. Data Preprocessing

Data preprocessing was performed to improve dataset quality and analysis performance.

Tasks Performed

 Checked missing values
 Removed duplicate records
 Verified data types
 Cleaned transaction data
 Created risk categories
 Ensured data consistency

📊 2. Exploratory Data Analysis (EDA)

EDA was performed to understand transaction behavior and fraud patterns using statistical and visualization techniques.

📌 Analysis Performed
Fraud vs Normal Transaction Analysis
Compared fraud and normal transaction counts
Analyzed fraud imbalance
Transaction Amount Distribution
Studied spending behavior
Identified transaction spread
Time-Based Analysis
Analyzed transaction timing patterns
Risk Behavior Analysis
Classified low-risk and high-risk transactions
Correlation Analysis
Identified relationships among features
🔍 Key Influencing Factors Identified

The following factors strongly influenced fraud behavior:

Transaction amount
Transaction timing
Feature correlations
Unusual spending patterns
Risk categories
📈 3. Data Visualization

Visualization techniques were used to understand fraud patterns and transaction trends.

📊 Visualizations Used
Visualization	Purpose
<img width="584" height="357" alt="vis1" src="https://github.com/user-attachments/assets/957d5d02-ace8-4937-aba7-8f4315caa3bf" />
<img width="640" height="424" alt="vis2" src="https://github.com/user-attachments/assets/aa26f16e-9b87-4bd4-a627-ed983734a883" />

Bar Charts	Fraud distribution
Histograms	Transaction amount analysis
Scatter Plots	Relationship analysis
Box Plots	Outlier detection
Heatmaps	Correlation analysis
📉 Fraud Distribution Analysis

Analyzed:

Fraud transactions
Normal transactions

Purpose:

Understand fraud occurrence
Compare class distribution
📌 Transaction Amount Analysis

Histograms and boxplots were used to:

Analyze spending patterns
Detect unusual transactions
Identify outliers
📌 Correlation Heatmap

Heatmaps were used to identify:

Strong feature relationships
Fraud influencing variables
Data dependencies
📦 4. Feature Engineering

Additional processing was performed to improve analysis quality.

Tasks Included
Risk level classification
Data transformation
Feature organization
Numerical processing
⚠️ 5. Risk Analysis

Transactions were categorized into:

Risk Level	Description
Low Risk	Small transactions
Medium Risk	Moderate transaction values
High Risk	Large suspicious transactions

Purpose:

Identify suspicious transaction behavior
Support fraud monitoring
🤖 6. Machine Learning Model
Linear Regression

A Linear Regression model was used for predictive analysis.

📌 Model Purpose

The model helps:

Predict transaction trends
Analyze transaction behavior
Understand financial activity patterns
📥 Independent Variable
Time
📤 Dependent Variable
Transaction Amount
🔀 7. Train-Test Split

The dataset was divided into:

Dataset Type	Purpose
Training Data	Train model
Testing Data	Evaluate performance
🏋️ 8. Model Training

The Linear Regression model was trained using Scikit-learn.

Purpose:

Learn transaction patterns
Analyze financial trends
Build prediction capability
📈 9. Prediction

The trained model generated predictions for:

Transaction amount trends
Financial behavior analysis
📊 10. Model Evaluation

The model was evaluated using:

R² Score

Measures prediction performance.

Residual Analysis

Analyzes prediction errors.

Accuracy Evaluation

Measures overall model effectiveness.

📊 11. Dashboard Visualization

<img width="1127" height="441" alt="dashboard" src="https://github.com/user-attachments/assets/86b7806b-c4ef-46c6-97ce-a0e23811360e" />
<img width="1142" height="407" alt="dashboard2" src="https://github.com/user-attachments/assets/ac7520dd-b940-421f-a0fd-48eb0c4dc742" />


Interactive dashboards were created using:

Plotly

📌 Dashboard Features

 Fraud transaction distribution
 Transaction amount visualization
 Scatter plot analysis
 Risk level charts
 Correlation heatmap
 Dynamic visualizations
 Interactive filtering

💻 Technologies Used
Technology	Purpose
Python	Programming
Pandas	Data Analysis
NumPy	Numerical Operations
Matplotlib	Visualization
Seaborn	Statistical Visualization
Plotly	Interactive Dashboard
Scikit-learn	Machine Learning
Jupyter Notebook	Development Environment
🔍 Key Insights

The project identified several important fraud-related patterns:

 Fraud transactions often show unusual transaction amounts
 Some transaction patterns are strongly related to fraud
 Outlier transactions indicate suspicious behavior
 Risk classification improves fraud analysis
 Correlation analysis helps identify important influencing features

🎯 Expected Outcomes

 Better fraud detection understanding
 Improved transaction risk analysis
 Enhanced fraud prevention strategies
 Interactive fraud analytics dashboard
 Better financial security support

📌 Conclusion

This project demonstrates how data analytics, visualization, and machine learning can support fraud detection systems in financial environments.

By combining:

EDA
Statistical analysis
Linear Regression
Interactive dashboards

the system provides meaningful insights into transaction behavior and supports better fraud risk management strategies.

The project also improves understanding of:

Data preprocessing
Fraud analytics
Machine learning workflows
Dashboard development
Financial transaction analysis
🚀 Future Enhancements

Future improvements may include:

Logistic Regression
Random Forest Classifier
XGBoost
Deep Learning Models
Real-time Fraud Detection
Advanced Dashboard Analytics
AI-based Fraud Monitoring Systems
