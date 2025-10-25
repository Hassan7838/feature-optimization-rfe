# feature-optimization-rfe 
"Feature Optimization for Classification Problems using Recursive Feature Elimination (RFE)"

This project demonstrates the application of **Recursive Feature Elimination (RFE)** to optimize features for a classification problem using the **Titanic dataset**. The goal is to enhance model interpretability and performance by selecting only the most impactful features that contribute to accurate survival prediction.

# Project Overview

Feature selection is a crucial step in building efficient machine learning models. This project applies **RFE** with a base classifier (Logistic Regression or Decision Tree) to identify the most significant features in the Titanic dataset and compares model performance before and after feature optimization.

# Project Goals

1. **Dataset Preparation**
   - Utilize the Titanic dataset from Kaggle.
   - Clean, preprocess, and encode categorical variables.
   - Define features (`X`) and the target variable (`y = Survived`).

2. **Recursive Feature Elimination (RFE)**
   - Apply RFE with a chosen estimator (e.g., Logistic Regression or Decision Tree).
   - Determine the optimal subset of features using cross-validation (RFECV).
   - Identify and visualize selected features.

3. **Model Training and Evaluation**
   - Train a baseline model using all available features.
   - Train an optimized model using only the RFE-selected features.
   - Compare both models using metrics:
     - Accuracy  
     - Precision  
     - Recall  
     - F1-score  

4. **Results Analysis**
   - Present selected features and their significance.
   - Compare model performance (before vs. after RFE).
   - Discuss benefits of feature optimization — improved generalization, reduced complexity, and faster computation.

# Tools and Libraries

- Python 3.x  
- Pandas – for data handling and preprocessing  
- NumPy – for numerical operations  
- Scikit-learn – for RFE, modeling, and evaluation metrics  
- Matplotlib / Seaborn – for visualizations  

# Dataset Information

**Dataset:** [Titanic - Machine Learning from Disaster (Kaggle)](https://www.kaggle.com/competitions/titanic)  
- The dataset is **not uploaded** due to size constraints.  
- You can download it directly from Kaggle and place it in your working directory.

## ⚙️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/feature-optimization-rfe.git
