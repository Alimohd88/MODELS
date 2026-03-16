# Student Marks Predictor

This project predicts student marks based on the number of study hours using a Machine Learning Linear Regression model.

---

## Problem Statement

Students often want to estimate their expected marks based on how many hours they study.

---

## Solution

A **Linear Regression model** is used to learn the relationship between:

- Study Hours
- Student Marks

The trained model predicts marks for new study hour inputs.

---

## Dataset

The dataset contains two columns:

| Study Hours | Marks |
|-------------|------|
| 2 | 25 |
| 5 | 55 |
| 7 | 70 |
| 9 | 90 |

---

## Visualization

Relationship between study hours and marks:

![Study Hours vs Marks](study_hours_vs_marks.png)

This shows a **positive linear relationship** between study time and marks.

---

## Machine Learning Model

Algorithm used:

**Linear Regression**

Formula:

y = mx + c

Where:

- y = predicted marks
- x = study hours
- m = slope
- c = intercept

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## Example Prediction

Input:

Study Hours = 7

Output:

Expected Marks ≈ 70

---

## Project Structure
