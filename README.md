# Elevate_Lab-Task-7
# Task 7: Support Vector Machines (SVM) Analysis

##  Overview

This project demonstrates the application of Support Vector Machines (SVM) for binary classification using both linear and non-linear kernels. The dataset used is a structured binary classification dataset (e.g., Breast Cancer Dataset). The project walks through model training, visualization, tuning, and evaluation.

---

##  Objective

- Train SVM models using **linear** and **RBF kernels**.
- Visualize decision boundaries using PCA for 2D projection.
- Tune hyperparameters (`C`, `gamma`) using **GridSearchCV**.
- Evaluate model performance using **cross-validation** and metrics like accuracy and classification report.

---

## Tools and Libraries

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

---

##  Methodology

1. **Data Preparation**:
   - Load dataset
   - Standardize features
   - Apply PCA for 2D visualization

2. **Model Training**:
   - Train SVM with `linear` and `rbf` kernels.

3. **Visualization**:
   - Plot decision boundaries to observe model behavior.

4. **Hyperparameter Tuning**:
   - Use `GridSearchCV` to find optimal `C` and `gamma`.

5. **Evaluation**:
   - Accuracy and classification report on test set.
   - Cross-validation score on training data.

---

##  Key Concepts

- **Support Vector**: Data points closest to decision boundary.
- **Margin Maximization**: SVM maximizes the margin between classes.
- **Kernel Trick**: Allows SVM to separate data in higher dimensions.
- **Regularization (C)**: Controls the trade-off between margin and misclassification.
- **Gamma (RBF Kernel)**: Controls influence of individual points.

---

##  Conclusion

- Linear SVMs perform well on linearly separable data.
- RBF kernel allows flexibility for complex, non-linear boundaries.
- Hyperparameter tuning significantly improves model performance.
- SVM is a powerful, robust classifier for binary tasks, especially with proper scaling and tuning.

---
