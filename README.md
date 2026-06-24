# Retail Sales Analysis and Profit Prediction

## Objective
This project analyzes a real-world retail sales dataset and builds a machine learning model to predict profit. The goal is to understand business performance, identify important sales trends, and apply data science techniques in a real-world retail domain.

## Dataset
The dataset used in this project contains retail order information such as:
- Category
- Sub-Category
- Region
- Segment
- Sales
- Quantity
- Discount
- Profit

## Tools and Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow

### 1. Data Loading and Understanding
- Loaded the Superstore retail dataset using Pandas
- Checked shape, column names, and statistical summary
- Verified missing values in the dataset

### 2. Exploratory Data Analysis (EDA)
Performed analysis to identify sales and profit trends:
- Sales by Category
- Profit by Category
- Sales by Region
- Top 10 Sub-Categories by Sales
- Correlation Heatmap for numerical features

### 3. Machine Learning Model
Built a **Random Forest Regressor** model to predict **Profit** using:
- Sales
- Quantity
- Discount
- Category
- Region
- Segment

### 4. Model Evaluation
Evaluated the model using:
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

### 5. Feature Importance
Generated a feature importance chart to identify which features most influence profit prediction.

## Output Files
This project generates the following visualization files:
- `sales_by_category.png`
- `profit_by_category.png`
- `sales_by_region.png`
- `top_subcategories.png`
- `correlation_heatmap.png`
- `feature_importance.png`

## Key Insights
- Retail sales vary significantly across categories and regions.
- Some sub-categories contribute more strongly to overall sales.
- Discount and sales have a direct influence on profit.
- Machine learning can be used to estimate profit from retail business features.

## Outcome
This project demonstrates end-to-end data analysis and predictive modeling on a real-world retail dataset using Python and machine learning.
