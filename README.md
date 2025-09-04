# students_score_prediction
# Student Score Prediction Model

This project predicts student exam scores based on study-related features such as **hours studied, attendance, and access to resources**.  

## Project Overview
- The model was first built using **Linear Regression**, which assumes a straight-line relationship between the features and the exam scores.  
- To improve performance and capture non-linear patterns, the model was then compared with **Polynomial Regression (degree 2)**.  

## Features
- **Data Preprocessing:** Splitting data into training and testing sets  
- **Model Training:** Using Linear Regression and Polynomial Regression  
- **Model Evaluation:** Comparing results using metrics such as:  
  - Mean Absolute Error (MAE)  
  - Mean Squared Error (MSE)  
  - Root Mean Squared Error (RMSE)  
  - R² Score  

## Results
- The Polynomial Regression (degree 2) outperformed Linear Regression, giving a better R² score and capturing the relationship between features and scores more accurately.  

## Files
- `student_score_prediction_model.ipynb` → Jupyter Notebook containing the full implementation and results.  

## How to Run
1. Clone or download this repository  
2. Open the notebook in **Jupyter Notebook** or **Google Colab**  
3. Run all cells to train and evaluate the models  

---

 This project demonstrates the difference between **Linear Regression** and **Polynomial Regression** when applied to student performance prediction.


