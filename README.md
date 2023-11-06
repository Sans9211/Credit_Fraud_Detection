# Credit Card Fraud Detection using Machine Learning

## Project Description:

The aim of this project is to detect credit card fraud using machine learning algorithms. The project utilizes a dataset obtained from Kaggle in CSV format, which was converted into a Pandas DataFrame. The key steps of the project involved Exploratory Data Analysis (EDA) to understand the data, including checking for data types, statistical information, size, and outliers through interquartile range (IQR) analysis. Visualization techniques such as box plots were used to identify outliers.

### Data Preprocessing:

- Outlier handling was performed using the IQR method.
- The dataset was unbalanced, so under-sampling was applied to address this issue.
- Standardization was applied to the data due to the presence of outliers, using the StandardScaler from scikit-learn.

### Feature Selection:

Relevant features were selected using correlation analysis to identify the most impactful variables in the dataset.

### Model Training:

The project utilized three machine learning algorithms:

1. Logistic Regression (LR)
2. Decision Tree
3. Random Forest

### Model Performance:

1. Logistic Regression (LR):
   - Binary classification was used due to two classes in the target column.
   - Achieved an accuracy of 91% on the training set and 90% on the testing set.

2. Decision Tree:
   - To address overfitting, hyperparameter tuning was applied.
   - Achieved an accuracy of 94% on the training set and 92% on the testing set.

3. Random Forest:
   - Achieved an initial accuracy of 100% on the training set and 94% on the testing set.
   - Hyperparameter tuning further improved the accuracy to 99% on the training set and 95% on the testing set.

### Conclusion:

Based on the comparison of the three models, the Random Forest algorithm demonstrated the most robust performance, achieving a 99% accuracy on the training set and 94% accuracy on the testing set. As a result, the Random Forest algorithm was selected as the final model for credit card fraud detection in this project.

### Contact
for further enquiries please visit www.linkedin.com/in/sanskriti-choudante

