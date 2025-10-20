# 🎓 Student Performance Analysis and Prediction (Portuguese Dataset)

This project explores and predicts **student performance** using the **Kaggle “Student Performance (Portuguese)” dataset**.  
It applies **Exploratory Data Analysis (EDA)** and a **Deep Learning (MLP)** model to predict whether a student will **pass or fail** based on demographic, social, and academic factors.

---

## 📊 Project Overview

- **Dataset:** `student-por.csv` from [Kaggle Student Performance Dataset](https://www.kaggle.com/datasets/larsen0966/student-performance-data-set)
- **Goal:** Predict student pass/fail status (`G3 ≥ 10 → pass`) using demographic and study-related features.
- **Tech Stack:**
  - Python 🐍
  - Pandas, NumPy, Matplotlib, Seaborn
  - Scikit-Learn
  - TensorFlow / Keras
  - Missingno (for missing value visualization)

---

## 🚀 How to Run the Project

### Option 1 — Google Colab (Recommended)
1. Open the notebook directly in Colab:  
   [![Open In Colab]([https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/USERNAME/student-performance-analysis/blob/main/student_performance_analysis.ipynb](https://colab.research.google.com/drive/1My0AkD6nLOz_YBpIqiVI4MvW1hov4Buz?usp=sharing))
2. Upload the dataset file: **`student-por.csv`**
3. Run all cells (Ctrl + F9 → “Run All”)
4. View training accuracy, loss plots, ROC curve, and confusion matrix.

### Option 2 — Local Setup
```bash
# Clone the repository
git clone https://github.com/USERNAME/student-performance-analysis.git
cd student-performance-analysis

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow plotly missingno

# Run the notebook
jupyter notebook student_performance_analysis.ipynb
