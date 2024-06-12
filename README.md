**Project Summary: Predicting Mental Disorder Burden using Linear Regression**

This project aimed to predict the burden of mental disorders in terms of Disability-Adjusted Life Years (DALYs) using a linear regression model. The dataset used for this analysis contained information on the prevalence of various mental disorders across different countries and years.

### Overview
- **Objective**: Predict the DALYs attributed to mental disorders based on various prevalence factors.
- **Dataset**: The dataset consists of 6840 observations and 11 features, including prevalence rates of different mental disorders and demographic information, spanning from 1990 to 2019.
- **Tools and Libraries**: Python, pandas, NumPy, Matplotlib, Seaborn, scikit-learn.

### Steps Involved:

1. **Exploratory Data Analysis (EDA)**:
   - Reviewed basic information, such as data types and non-null counts.
   - Examined summary statistics to understand the distribution of variables.
   - Checked for missing values to ensure data completeness.

2. **Data Preprocessing**:
   - Removed non-numeric columns and dropped rows with missing values.
   - Encoded categorical variables using one-hot encoding.

3. **Model Building**:
   - Split the dataset into training and testing sets (80-20 ratio).
   - Utilized linear regression to train the model on the training data.

4. **Model Evaluation**:
   - Evaluated the trained model on both the training and testing sets.
   - Assessed performance using mean squared error (MSE) and R-squared metrics.

5. **Visualizations**:
   - Visualized the predicted vs. actual values using scatter plots.
   - Analyzed the distribution of residuals with a histogram.

### Results:
- **Training Results**:
  - Mean Squared Error (Train): *mse_train*
  - R-squared (Train): *r2_train*

- **Testing Results**:
  - Mean Squared Error (Test): *mse_test*
  - R-squared (Test): *r2_test*

### Conclusion:
The linear regression model achieved *mse_train* MSE and *r2_train* R-squared on the training set, and *mse_test* MSE and *r2_test* R-squared on the testing set. These metrics indicate that the model performs reasonably well in predicting mental disorder burden based on the provided features.
