# Pattern Recognition & Machine Learning Assignment

## 📌 Description

This repository contains the final project for the course **Pattern Recognition & Machine Learning**.

The project is divided into four main parts:
- **Part A**: Classification using **Maximum Likelihood Estimation (MLE)**
- **Part B**: Classification using **Bayesian Parameter Estimation**
- **Part C**: **Decision Tree** and **Random Forest** classifiers applied on the **Iris dataset**
- **Part D**: Classification of unseen data using a custom model trained on a **high-dimensional dataset**

---

## 🧠 Tools & Technologies

- Python
- NumPy, SciPy, Matplotlib
- Scikit-learn (`DecisionTreeClassifier`, `RandomForestClassifier`)
- Jupyter Notebooks

---

## ✅ How to Run

1. Open the `.ipynb` notebooks in **Jupyter** or **Google Colab**.
2. Run the code cells for each part in order.
3. Load predictions from Part D with:

```python
import numpy as np
labels = np.load("labels.npy")
print(labels.shape)  # Should be (6955,)```

---

## 📄 License 

This repository is intended for academic use only.

Do not copy or reuse without permission.

