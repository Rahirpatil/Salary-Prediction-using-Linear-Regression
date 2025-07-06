# 💼 Salary Prediction using Linear Regression

This project focuses on predicting a person's salary based on their years of experience using **Linear Regression**. It demonstrates a simple yet powerful approach to solving regression problems in machine learning.

---

## 📘 Project Overview

The objective of this project is to:
- Understand the relationship between years of experience and salary
- Build a Linear Regression model to predict salary
- Visualize the data and the regression line
- Evaluate predictions using test data
- Accept user input for prediction

---

## 📁 Dataset

- **Filename**: `salary_data.csv`
- **Columns**:
  - `YearsExperience`: Number of years a person has worked
  - `Salary`: Salary corresponding to the experience

This is a small, commonly used dataset ideal for learning regression techniques.

---

## 🛠️ Technologies Used

- Python
- pandas
- matplotlib
- scikit-learn

---

## 🔁 Workflow

1. **Load the Data**  
   Read the dataset using `pandas`.

2. **Visualize the Data**  
   Create a scatter plot to see the trend between experience and salary.

3. **Split the Data**  
   Use `train_test_split` to divide data into training and testing sets.

4. **Train the Model**  
   Apply `LinearRegression` from `sklearn` to fit the model on training data.

5. **Make Predictions**  
   Predict salary values using test data and user input.

6. **Visualize the Regression Line**  
   Plot the best-fit line along with the original training data.

---

## 📈 Example Use Case

The user provides the number of years of experience, and the model returns the predicted salary based on learned patterns from the training data.

---

## ✅ Key Features

- Easy-to-follow structure for Linear Regression
- Beginner-friendly code
- Real-world application of supervised learning
- Visual representation of training data and model predictions

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/salary-prediction.git
   cd salary-prediction
