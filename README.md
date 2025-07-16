# 🧠 Breast Cancer Diagnosis — Logistic Regression from Scratch

This project implements logistic regression from scratch (without using ML libraries like scikit-learn) to classify breast cancer as malignant or benign using the [Breast Cancer Wisconsin Diagnostic dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data). The project also includes full exploratory data analysis, feature scaling, visualizations, model evaluation, and a user-friendly input prediction interface.

---

## 📁 Dataset

- Source: [Kaggle - Breast Cancer Wisconsin Diagnostic Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- 569 records with 30 numeric features
- Target: diagnosis — Malignant (M) or Benign (B)

---

## 🧪 Project Highlights

- Logistic Regression implemented *from scratch*
- No use of high-level ML libraries for modeling
- End-to-end pipeline: preprocessing → training → evaluation → live predictions
- Rich *data analysis and visualizations* included
- Scalable and modular codebase with clean docstrings and comments

---

## 📊 Features Used

- Radius, Texture, Perimeter, Area, Smoothness (mean, standard error, worst)
- Compact feature selection not used — all 30 numeric features are scaled and used

---

## 📉 Visualizations

- 📌 Diagnosis class distribution (Benign vs Malignant)
- 🔥 Correlation heatmap
- 🔍 Pairplots for selected features
- 🧮 Cost function convergence over training epochs

---
![image](https://github.com/user-attachments/assets/2f80bc40-37c0-4c3f-9ade-4d427dd3c8da)
![image](https://github.com/user-attachments/assets/544cec98-7588-4763-8916-8b6c245a75ac)


## 🧠 Model Overview

- *Algorithm*: Logistic Regression
- *Loss Function*: Binary Cross-Entropy
- *Optimization*: Gradient Descent (custom implementation)
- *Feature Scaling*: StandardScaler from sklearn.preprocessing

---

## 📈 Results

- Training Accuracy: ~98–99% (depending on initial weights and learning rate)
- Final cost convergence visualized
- Real-time prediction interface with manual user input

---

## 💻 Usage

1. Clone the repository:
    bash
    git clone https://github.com/Purushottam0001/breast-cancer-logistic.git
    cd breast-cancer-logistic
    

2. Install required libraries:
    bash
    pip install numpy pandas matplotlib seaborn scikit-learn
    

3. Run the Jupyter Notebook:
    bash
    jupyter notebook
    

4. Execute all cells step by step.

---

## 🧑‍⚕ Example Prediction

```txt
Enter 30 feature values separated by spaces:
17.99 10.38 122.8 1001.0 0.1184 ... (total 30 values)

## 📌 Future Improvements
- Add test/train split and validation
- GUI or Web App interface using Streamlit or Flask
- Model comparison with scikit-learn implementation
