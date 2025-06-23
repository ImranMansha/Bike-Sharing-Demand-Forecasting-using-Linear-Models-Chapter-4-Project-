# Bike Sharing Demand Forecasting using Linear Models

This project applies core machine learning techniques from **Chapter 4: Training Models** of the book _Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow_ by Aurélien Géron, using a real-world dataset from the UCI ML Repository.

## Contents of This Notebook

- ✔️ Solved exercises from Chapter 4 (conceptual understanding)
- ✔️ Comparative notes on Gradient Descent and Regularization
- ✔️ Data preprocessing and feature engineering (polynomial expansion)
- ✔️ Model training using:
  - Linear Regression
  - Ridge Regression
  - Lasso Regression
  - Stochastic Gradient Descent (SGD)
- ✔️ Learning curve visualizations
- ✔️ Hyperparameter tuning using GridSearchCV
- ✔️ Feature importance analysis
- ✔️ Final model comparison and practical insights

---

## Dataset Used

**Bike Sharing Dataset**  
- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset)  
- File used: `day.csv`  
- Target: `cnt` (Total bike rentals per day)  
- Features include: season, holiday, weekday, temperature, humidity, weather, etc.

---

## Model Performance Summary

| Model              | RMSE         | R² Score |
|-------------------|--------------|----------|
| Linear Regression | 823,795.06   | 0.795    |
| Ridge Regression  | 529,583.93   | 0.868    |
| Lasso Regression  | 598,762.48   | 0.851    |
| SGD Regressor     | ❌ Diverged  | ❌ Failed |

---

## Key Learnings

- Ridge Regression gave the best generalization performance.
- Polynomial features increased complexity, requiring regularization.
- Feature importance analysis revealed that weather, temperature, and season strongly influence rental demand.
- Gradient Descent methods require careful tuning (SGD can diverge without it).

---

## Project Structure


---

## 📜 License

This project is for academic use based on the book _Hands-On Machine Learning_. Dataset provided by [UCI](https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset).

---

## ✍️ Author

**Imran Mansha**  
_Machine Learning Intern | BS IT Student_  
📧 imansha752@gmail.com
