# Machine Problem No. 2: Evaluating Machine Learning Model Performance

This repository contains the implementation and evaluation of a **Logistic Regression classifier** as part of Machine Problem No. 2 for the course **CSST102 - Basic Machine Learning**.

## 📊 Dataset Used
- **Dataset**: Breast Cancer Wisconsin (Diagnostic) Dataset
- **Source**: Built into `sklearn.datasets`
- **Description**: This dataset contains features computed from digitized images of fine needle aspirates (FNA) of breast masses. The goal is to classify tumors as either **malignant (0)** or **benign (1)**.
- **Features**: 30 numeric features describing characteristics of cell nuclei.
- **Samples**: 569 instances.

> ✅ *Note: This dataset was chosen for its clean structure, no missing values, and suitability for binary classification.*

## 🧪 Experiment Overview
This project follows a complete machine learning workflow:
1. **Data Preprocessing**: Standardizing features.
2. **Train-Test Split**: 80% training, 20% testing.
3. **Model Training**: Logistic Regression with default parameters.
4. **Model Evaluation**:
   - Confusion Matrix & Classification Metrics (Accuracy, Precision, Recall, F1)
   - 5-Fold Cross-Validation (Mean Accuracy ± Std Dev)
   - Learning Curve Analysis (Training vs Validation Accuracy)

## 🚀 How to Run the Code

1. **Open in Google Colab** (Recommended):
   - Click this button to open the notebook directly in Google Colab:
     [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-username/CSST102/blob/main/MP2/logistic_regression.ipynb)
   - *(Replace `your-username` with your actual GitHub username)*

2. **Run Locally**:
   - Clone this repository:
     ```bash
     git clone https://github.com/your-username/CSST102.git
     cd CSST102/MP2
     ```
   - Install required packages:
     ```bash
     pip install scikit-learn matplotlib numpy pandas jupyter
     ```
   - Open the notebook:
     ```bash
     jupyter notebook logistic_regression.ipynb
     ```
   - Run all cells to reproduce results.

## 📁 File Structure
CSST102/
└── MP2/
├── logistic_regression.ipynb # Jupyter Notebook with full code & comments
├── learning_curve.png # Visualization of the learning curve
├── confusion_matrix.png # Visualization of the confusion matrix
├── cross_validation.txt # Summary of 5-Fold CV results
├── report.pdf # Short reflection report (1–2 pages)
└── README.md # This file


## 📝 Notes
- All visualizations (`learning_curve.png`, `confusion_matrix.png`) are saved automatically when you run the notebook.
- The `cross_validation.txt` file is generated during execution.
- The `report.pdf` summarizes key findings and interpretations as required by the assignment.

---

*Prepared by: Kean Gabriel E. Salvahan*
*Section: BSCS - 3B*
*Academic Year: 2025-2026*
