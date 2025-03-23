Lead Conversion Prediction Using Linear Regression
📌 Overview
This project builds a Linear Regression model to predict lead conversion rates based on user interactions on a website. The dataset contains features like Total Visits, Time Spent, Page Views Per Visit, Activity Score, and Profile Score, which are used to train the model.

📂 Dataset
The dataset, Leads (1).csv, includes:

TotalVisits: Number of times the user visited the website

Total Time Spent on Website: Time spent on the website

Page Views Per Visit: Number of pages viewed per session

Asymmetrique Activity Score: Engagement score based on user activity

Asymmetrique Profile Score: Score based on the user’s profile strength

Converted: Target variable (1 = converted, 0 = not converted)

⚙️ Model Training
Preprocessing: Missing values removed

Train-Test Split: 80% training, 20% testing

Model: Linear Regression

Evaluation:

Mean Squared Error (MSE)

R-squared Score (R²)

📊 Visualizations
Correlation Heatmap – Shows relationships between features

Conversion Distribution – Displays the balance of converted vs. non-converted leads

Actual vs. Predicted Values – Scatter plot to assess model performance

Residual Plot – Distribution of errors in predictions

🔍 Key Findings
The model predicts conversion probabilities based on user interactions

Visualization of actual vs. predicted values helps assess model accuracy

Residual analysis checks for potential biases in predictions
