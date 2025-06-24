# 📊 Data Analysis and Modeling Tasks

This project notebook consists of three core exploratory and predictive tasks:

---

##  Task 1: Iris Dataset Visualization

###  Objective
Explore the famous Iris dataset to understand how different features (e.g., sepal length, sepal width) vary across iris species and visualize their relationships.

###  Approach
- Loaded the built-in seaborn `iris` dataset.
- Used scatter plots, histograms (with and without KDE), and box plots to explore feature distributions and class separability.

###  Insights
- **Setosa** species is clearly distinguishable based on sepal dimensions.
- **Versicolor** and **Virginica** overlap more but still show variance in sepal length.
- Box plots revealed **Setosa** has the smallest sepal length range, while **Virginica** has the largest.

---

##  Task 2: Credit Risk Prediction (Loan Status)

###  Objective
Predict whether a loan will be approved (`Loan_Status`) based on applicant financial and demographic details.

###  Approach
- Cleaned missing values and encoded categorical variables.
- Used **Logistic Regression** to build a binary classifier.
- Evaluated model with accuracy score and confusion matrix.
- Visualized:
  - Distribution of loan amounts
  - Loan approval rates by education
  - Applicant income by loan status

###  Results
- Achieved a test accuracy of approximately **79%**.
- Key insights:
  - Graduates had a slightly higher approval rate.
  - Higher applicant income didn't always guarantee approval — other factors like **credit history** played a role.

---

##  Task 3: Bank Customer Churn Prediction

###  Objective
Identify customers likely to **churn** (i.e., leave the bank) based on their profile and banking activity.

###  Approach
- Removed uninformative features (`CustomerId`, `RowNumber`, etc.).
- Encoded `Gender` and `Geography`.
- Trained a **Random Forest Classifier**.
- Evaluated the model using a classification report and confusion matrix.
- Visualized feature importances.

### Results
- The model performed well with solid classification metrics.
- **Most influential features**:
  - `Age`
  - `IsActiveMember`
  - `Balance`
  - `Geography_Germany`

---

## Conclusion

This notebook demonstrated:
- Effective **EDA and visualization** using Seaborn and Matplotlib.
- **Data cleaning and encoding** practices for supervised learning.
- Use of **classification models** (Logistic Regression, Random Forest) to solve real-world prediction tasks.
- Extraction of **meaningful insights** from model performance and feature importances.
