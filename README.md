# 🧠 Python Programming for AI and Machine Learning

A structured, hands‑on collection of Python notebooks and scripts exploring the core concepts of **Machine Learning** and **AI** using real CSV datasets.  
This repository is designed as a clean, reproducible learning environment that demonstrates essential ML workflows, algorithm intuition, and practical implementation using Python.

The goal is not to build one large model, but to create a **modular ML playground** where each notebook focuses on a specific concept or algorithm — from Linear Regression to SVMs, Decision Trees, Random Forests, Clustering, and more.

---

## 🎯 Objectives

This repository aims to:

- Build intuition for fundamental ML algorithms  
- Practice Python‑based data analysis and preprocessing  
- Explore multiple datasets across different domains  
- Compare models and understand their strengths/limitations  
- Visualize results and decision boundaries  
- Develop clean, reproducible ML workflows  
- Create a portfolio‑ready collection of ML examples  

---

## 📁 Project Structure
```text
python-ai-ml/
│
├── data/
│   ├──boston_housing.csv
│   ├── dataset2.csv
│   └── ...
│
├── notebooks/
│   ├── 01_linear_regression.ipynb
│   ├── 02_logistic_regression.ipynb
│   ├── 03_svm.ipynb
│   ├── 04_decision_tree.ipynb
│   ├── 05_random_forest.ipynb
│   ├── 06_clustering.ipynb
│   └── 07_model_comparison.ipynb
│
├── src/
│   ├── train_model.py
│   └── utils.py
│
├── assets/                   # Non-code resources
│   ├── architecture_diag.png 
│   ├── regression_plot.png
│   ├── svm_boundary.png
│   ├── tree_visualization.png
│   └── metrics_table.png
│
├── results/                 # Generated artifacts from notebooks/scripts
│   └── plots/                # Saved charts/visualizations
│       └── linear_regression
|           |──  README.md
|           ├── residual_plot.png
|           ├── comparison_pred_vs_true.png
│           └── distribution_housing.png
|
├── README.md
└── requirements.txt
```

### **Folders Explained**

- **data/**  
  Contains CSV datasets used in the notebooks.  
  (User‑provided or synthetic.)

- **notebooks/**  
  Each notebook focuses on one ML concept or algorithm.

- **src/**  
  Reusable Python modules for preprocessing, training, and evaluation.

- **assets/**  
  Plots and images used in the README or generated during experiments.

---

## 📚 Algorithms & Concepts Covered

### **Regression**
- Linear Regression  
- Polynomial Regression  
- Regularization (Ridge, Lasso)

### **Classification**
- Logistic Regression  
- Support Vector Machines (SVM)  
- Decision Trees  
- Random Forests  
- K‑Nearest Neighbors (KNN)

### **Unsupervised Learning**
- K‑Means Clustering  
- PCA (Dimensionality Reduction)

### **ML Fundamentals**
- Train/test split  
- Cross‑validation  
- Feature scaling  
- Handling missing data  
- Model evaluation metrics  
- Visualization of decision boundaries  
- Overfitting vs. underfitting  

---

## ▶️ Getting Started

### 1. Clone the repository

```bash
git clone [https://github.com/montahabouezzed-sys/python-ai-ml.git](https://github.com/montahabouezzed-sys/Python-for-AI-and-ML-Fundamentals)
cd python-ai-ml
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Open the notebooks
```bash
jupyter notebook
```

----

📊 Example Outputs
Visual examples (plots, decision boundaries, metrics tables) are stored in the assets/ folder and referenced inside the notebooks.

📄 License
This project is released under the MIT License.

🤝 Contributions
This repository is primarily a personal learning space, but suggestions and improvements are welcome.
