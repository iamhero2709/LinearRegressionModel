# Linear Regression from Scratch 🚀

Implementing a complete **Linear Regression** model from scratch using Python and NumPy, with a real-world dataset (Boston Housing).

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/your-repo-name/blob/main/linear_regression.ipynb)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Overview
This project demonstrates:
- Mathematical foundations of Linear Regression
- Implementation of **Gradient Descent**
- Feature scaling and bias term handling
- Performance evaluation (MSE, R² Score)
- Comparison with scikit-learn's implementation

## 📊 Dataset
**Boston Housing Dataset**:
- 506 samples, 13 features
- Target: Median house value (`MEDV`)
- Key Features: 
  - `RM` (Average rooms per dwelling)
  - `LSTAT` (% lower population status)
  - `PTRATIO` (Pupil-teacher ratio)

## 🛠️ Implementation Highlights

### Core Components
1. **Cost Function (MSE)**:
   ```math
   J(θ) = \frac{1}{2m} \sum_{i=1}^{m} (h_θ(x^{(i)}) - y^{(i)})^2

2.Gradient Descent:
```
θ_j := θ_j - α \frac{∂J(θ)}{∂θ_j}
```
3.Feature Scaling:

```
X_scaled = (X - μ) / σ

```
