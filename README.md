🏠 House Price Prediction – Data Preprocessing & EDA
This project demonstrates a comprehensive Exploratory Data Analysis (EDA) and data preprocessing pipeline for a house price prediction dataset (likely inspired by the Kaggle House Prices - Advanced Regression Techniques competition).

📌 Overview
The goal of this notebook is to prepare the data for predictive modeling by:

Handling missing values

Merging datasets

Feature engineering and encoding

Performing EDA using visualizations

Getting the dataset ready for regression models like Linear Regression, XGBoost, etc.

📂 Dataset
The project uses:

train.csv (provided by the competition or course)

test.csv for real-world test prediction

Focuses on SalePrice as the target variable

🔧 Techniques Used
✅ Preprocessing
Concatenated train and test sets for consistent preprocessing

Missing value treatment:

Dropping high-NA columns

Imputation using mean, mode, or 'NA' (depending on feature type)

Feature encoding:

Label encoding for ordinal variables

One-hot encoding for nominal categorical variables

📊 EDA
Heatmaps for correlation analysis

Box plots and histograms for target (SalePrice) distribution

Value counts to inspect categorical balance

🧠 (Ready for Modeling)
Final clean dataset can be used in regression models:

Linear Regression

Ridge/Lasso

XGBoost

Random Forest

📸 Sample Visualizations
Heatmap of top 15 correlated features with SalePrice

Boxplots for OverallQual, Neighborhood, etc.

Count plots for ordinal features like ExterQual, BsmtQual

💡 Key Insights
OverallQual and GrLivArea are highly correlated with SalePrice

Some features with high missing values (like PoolQC, MiscFeature) can be dropped

Combining train/test helps maintain consistent feature space after encoding

