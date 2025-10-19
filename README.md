# 📈 Linear Regression using Gradient Descent (Python)

This project demonstrates a simple implementation of **Linear Regression** using **Gradient Descent** in Python — without using any machine learning libraries like scikit-learn.

---

## 🧠 Concept

Linear Regression tries to fit a line of the form:

\[
y = θ₀ + θ₁x
\]

to minimize the **Sum of Squared Errors (SSE)** between the predicted values and the actual data.

Gradient Descent is used to iteratively update the parameters \( θ₀ \) and \( θ₁ \) using the following formulas:

\[
θ₀ := θ₀ - α \frac{∂(SSE)}{∂θ₀}
\]
\[
θ₁ := θ₁ - α \frac{∂(SSE)}{∂θ₁}
\]

---

## 🧩 Code Overview

### Libraries Used
- `numpy` → for numerical calculations  
- `matplotlib` → for data visualization

### Main Steps
1. Initialize training data arrays `x` and `y`
2. Initialize parameters:
   ```python
   theta_0 = 0
   theta_1 = 0
   alpha = 0.01
   num_iterations = 100
