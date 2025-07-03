# 🧠 AI & ML Internship - Task 7: Support Vector Machines (SVM)

## 📌 Objective
The goal of this task is to understand and implement Support Vector Machines (SVM) for **binary classification** using both **linear** and **non-linear (RBF)** kernels. We also visualize decision boundaries in 2D and tune hyperparameters to optimize model performance.

---

## 🗂️ Dataset
- **Name**: Breast Cancer Wisconsin Dataset  
- **Source**: `sklearn.datasets.load_breast_cancer()`  
- **Type**: Binary Classification  
- **Features**: 30 numerical features  
- **Target Classes**:  
  - 0 → Malignant  
  - 1 → Benign

---

## 🛠️ Tools & Libraries
- Python
- Scikit-learn (`sklearn`)
- NumPy
- Pandas
- Matplotlib
- PCA (for 2D visualization)

---

## 🧪 What I Did
1. Loaded and explored the Breast Cancer dataset.
2. Standardized the features using `StandardScaler`.
3. Reduced dimensions to 2 using PCA for plotting.
4. Trained two SVM models:
   - **SVM with Linear Kernel**
   - **SVM with RBF Kernel**
5. Visualized decision boundaries using 2D plots.
6. Tuned hyperparameters using `GridSearchCV`:
   - `C`: Regularization parameter
   - `gamma`: Kernel coefficient for RBF
7. Evaluated performance with:
   - Confusion matrix
   - Classification report
   - Cross-validation accuracy

---

## 📊 Results
- **Best Accuracy (CV)**: _[Add score here after running code]_
- **Best Parameters (Grid Search)**: _[Example: {'C': 1, 'gamma': 0.1}]_
- **Key Observations**:
  - Linear SVM performs well on separable data.
  - RBF SVM generalizes better for non-linear patterns.
  - PCA enables effective 2D visualization.

---

## 📈 Visualizations
Included decision boundary plots for both:
- `svm_linear_decision_boundary.png`
- `svm_rbf_decision_boundary.png`

---

## 🧠 Concepts Learned
- Margin maximization and support vectors
- Kernel trick for non-linear classification
- Regularization (`C`) and kernel coefficient (`gamma`)
- Hyperparameter tuning using cross-validation

---
