# Data Science Assessment - Technology Products Analysis

## Introduction
This project focuses on the data analysis and statistical modeling of a dataset related to various technology products. The process involved cleaning and transforming raw data, conducting exploratory data analysis (EDA), building predictive models, and creating an interactive dashboard for visualization.

The key components of the project include:
- Data Cleaning and Transformation
- Exploratory Data Analysis (EDA)
- Statistical Model Development
- Model Optimization
- Data Visualization through an interactive dashboard

## Dataset
The dataset, **Technology Products**, contains information on tech products, including product features, pricing, and customer ratings. The key columns include:
- `Product_ID`, `Product_Name`, `Category`, `Brand`
- `Price`, `Units_Sold`, `Customer_Rating`, `Launch_Year`
- `Processor_Type`, `RAM`, `Storage`, `Battery_Life`, `Operating_System`
- `Warranty_Period`

The dataset was used to clean, transform, and develop models throughout the analysis.

### Dataset Link:
[Original Dataset](https://drive.google.com/file/d/1z0_rR4CGKhLr3C--1kiqiBtBYVdi7k-j/view?usp=drive_link)

## Section 1: Data Cleaning and Transformation
### 1. Handling Missing Values:
- Identified missing values using `isnull().sum()`.
- Applied strategies like removing rows with excessive missing values or imputing using mean/median/mode.

### 2. Outlier Detection and Removal:
- Used the Interquartile Range (IQR) method to identify and remove outliers.
- Number of outliers removed: `{Number_of_outliers}`.

### 3. Data Transformation:
- Converted `Product_ID`, `Launch_Year`, `Warranty_Period` to integers.
- Created new features: `Success_Rate = Units_Sold * Customer_Rating`.
- Converted `Success_Rate` into categories: **Successful** and **Not Successful**.

### 4. Standardization:
- Standardized numerical features such as `Price` for consistent model training.

### Cleaned Dataset:
[Cleaned Dataset](https://drive.google.com/file/d/1JMGtVOBlfMLxeyIm_dgzuz-8vAjOzf9W/view?usp=drive_link)

---

## Section 2: Statistical Modeling
### 1. Exploratory Data Analysis (EDA):
- Analyzed data distribution, relationships between key variables using histograms, boxplots, scatter plots, and correlation matrix.

### 2. Model Development:
#### Target Variable: 
- **Units Sold** - Predict the number of units sold based on product attributes.

#### Model Used: 
- **Linear Regression** to predict `Units_Sold`.
- Features: `Price`, `Customer_Rating`, `RAM`, `Storage`, `Warranty_Period`.

#### Model Performance:
- RMSE: `{rmse_value}`
- R-squared: `{r2_value}`

### 3. Model Optimization:
#### K-Nearest Neighbors (KNN) and Naive Bayes:
- Two classification models were developed to predict product success (`Success_Category`).
- Applied feature scaling and hyperparameter tuning to improve performance.

#### Model Comparison:
- **KNN Accuracy**: `{knn_accuracy}`
- **Naive Bayes Accuracy**: `{nb_accuracy}`

#### Optimized Performance:
- **KNN Optimized Accuracy**: `{knn_optimized_accuracy}`

### Model Notebook:
[Jupyter Notebook](https://drive.google.com/file/d/1DgBnJFxNbQEDmLjtCvNxGLg-4GzP_oOQ/view?usp=drive_link)

---

## Section 3: Data Visualization - Interactive Dashboard
An interactive dashboard was created using **Power BI** to present insights in an easily understandable format for non-technical stakeholders. 

### Key Insights:
1. **Sales Performance**: Sales distribution by product category and brand.
2. **Customer Satisfaction**: Analyzed customer ratings and product feedback.
3. **Pricing Impact**: The correlation between pricing strategies and units sold.
4. **Yearly Trends**: Time-series analysis of sales trends and product launches.
5. **Operational Metrics**: Warranty claims and battery life analysis.

### Dashboard Link:
[Power BI Dashboard](https://drive.google.com/file/d/1cIgyeiUkl_ynlu6aSyoP4vF-bCsdjXoM/view?usp=drive_link)

---

## Conclusion
The project demonstrates the end-to-end process of data cleaning, EDA, model development, and visualization using a real-world dataset. The findings provide valuable insights into product performance, customer satisfaction, and business strategy optimization.
