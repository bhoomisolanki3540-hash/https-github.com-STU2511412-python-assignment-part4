# Student Performance Analysis & Prediction (Part 4)

## Objective
In this assignment, I worked on analysing student data, creating visualisations, and building a simple machine learning model to predict whether a student will pass or fail.  
The focus was on understanding the complete workflow from data analysis to prediction.

---

## What I Did

### Task 1: Data Exploration
- Loaded the dataset using pandas  
- Checked the structure of the data (rows, columns, data types)  
- Generated summary statistics to understand score distribution  
- Counted how many students passed and failed  
- Compared average subject scores for passing vs failing students  
- Found the student with the highest overall average  

---

### Task 2: Data Visualisation (Matplotlib)
I created multiple plots to better understand the data:

- Bar chart showing average score per subject  
- Histogram to see distribution of math scores  
- Scatter plot of study hours vs average score (Pass vs Fail)  
- Box plot comparing attendance of passing and failing students  
- Line plot showing math and science scores for all students  

All plots were labelled properly and saved as `.png` files.

---

### Task 3: Data Visualisation (Seaborn)
- Created bar plots comparing math and science scores based on pass/fail  
- Created a scatter plot with regression lines to see relationship between attendance and performance  
- Noticed that Seaborn made styling and grouping easier compared to Matplotlib  

---

### Task 4: Machine Learning
- Selected relevant features and target column  
- Split the data into training and testing sets  
- Scaled the features using StandardScaler  
- Trained a Logistic Regression model  
- Evaluated model performance on test data  
- Compared actual vs predicted results for test students  

---

### Feature Importance
- Extracted model coefficients to understand which features impact prediction  
- Visualised feature importance using a horizontal bar chart  

---

### Bonus: New Prediction
- Tested the model on a new student’s data  
- Predicted whether the student will pass or fail along with probability  

---

## How to Run
- Make sure required libraries are installed:

##**pip install pandas matplotlib seaborn scikit-learn**

- Run the notebook or Python file  
- Plots will be displayed and saved automatically  

---

## Concepts Used
- Pandas for data handling  
- Matplotlib & Seaborn for visualisation  
- Train-test split and feature scaling  
- Logistic Regression model  
- Model evaluation and interpretation  

---

## Files
- `part4_visualization_ml.ipynb`  
- `students.csv`  
- Plot images (`.png` files)  

---

## Author
Bhoomi Solanki
