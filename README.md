# Data Scientist Technical Assessment

This repository contains the solutions for the Data Scientist Technical Assessment. The project is structured into three main sections: Data Analysis and Modeling, Machine Learning Development, and Data Visualization and Communication.


---

## Section 1: Data Analysis and Modeling

### Task 1: Data Cleaning and Transformation
- **Objective:** Handle missing values, detect and manage outliers, standardize or normalize data, and transform categorical variables into numerical ones.
- **Code:** The process is documented in `code/SNS Task.ipynb`.
  
#### Steps:
1. **Missing Values:** Identified and handled missing values in critical columns.
2. **Outlier Detection:** Applied statistical methods to detect and handle outliers.
3. **Data Normalization:** Standardized features such as `Price` to ensure uniformity.
4. **Feature Engineering:** Created new features like `Price_per_GB` for more informative analysis.

- **Deliverable:** The cleaned dataset is available in `data/Cleaned Dataset.csv`.

### Task 2: Exploratory Data Analysis (EDA) and Statistical Modeling
- **Objective:** Perform EDA to visualize relationships and develop a statistical model to predict a target variable.
- **Code:** Detailed in `code/SNS Task.ipynb`.

#### Steps:
1. **EDA:** Visualized correlations between `Price`, `Units Sold`, and `Customer Rating`.
2. **Model Selection:** Chose `Units Sold` as the target variable for a linear regression model.
3. **Model Development:** Developed the model using features like `Price`, `Category`, and `Brand`.
4. **Results:** Visualized the relationship between price and sales, and discussed assumptions made for the model.

---

## Section 2: Machine Learning Development

### Task 1: Model Development
- **Objective:** Select, train, and evaluate a machine learning model.
- **Code:** Available in `code/SNS Task.ipynb`.

#### Steps:
1. **Model Selection:** Used Random Forest Regression to predict `Units Sold`.
2. **Data Split:** Divided the data into 80% training and 20% testing sets.
3. **Model Training:** Trained the model on the training set.
4. **Evaluation:** Evaluated using RMSE, which was appropriate for the regression task.

### Task 2: Model Optimization
- **Objective:** Optimize the selected machine learning model for better performance.
  
#### Steps:
1. **Hyperparameter Tuning:** Applied grid search to optimize the Random Forest model.
2. **Cross-Validation:** Used cross-validation to validate the model performance.
3. **Result Comparison:** Improved RMSE compared to the base model.

- **Deliverable:** Optimized model code is included in `code/SNS Task.ipynb`.

---

## Section 3: Data Visualization and Communication

### Task 1: Visualization Dashboard
- **Objective:** Create an interactive dashboard using Power BI to present key insights.
- **File:** The Power BI dashboard can be found in `visualizations/Dashboard.pbix`.

#### Key Insights:
- **Sales Performance:** Visualized the distribution of sales across different product categories and brands.
- **Customer Satisfaction:** Analyzed customer ratings per product and brand, identifying areas for improvement.
- **Pricing Impact:** Examined how pricing affected unit sales, helping to form pricing strategies.

### Task 2: Presentation
- **Objective:** Summarize the entire approach and findings in a 5-minute presentation.
- **File:** The PowerPoint presentation with speaker notes is available in `presentation/Presentation.pptx`.

---

## Submission Instructions
- **GitHub Repository:** Ensure that all files are included in the repository.
- **Google Drive:** The cleaned dataset, models, dashboard, and presentation have been submitted via the Google Drive link.

---

## Contact Information
For any queries regarding this assessment, please contact [Your Email].



