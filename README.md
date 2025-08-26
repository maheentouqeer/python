# Titanic ML Assignment - Maheen Touqeer

End-to-end Machine Learning project using the **Kaggle Titanic dataset**.

> **How to use the real Kaggle dataset:**  
> 1) Download `train.csv` from Kaggle's Titanic competition page.  
> 2) Place it here: `data/train.csv`  
> 3) Open the notebook and run all cells to regenerate metrics and plots.  

## 📌 Pipeline
1. Data Loading (from `data/train.csv`)  
2. Cleaning & Preprocessing (missing values, encoding, scaling if needed)  
3. EDA (distributions, survival by class/sex, correlation heatmap)  
4. Feature Engineering (`FamilySize`, `IsAlone`)  
5. Model Training (LogReg, Decision Tree, Random Forest, SVM)  
6. Evaluation (accuracy, confusion matrix, ROC curve)  
7. Conclusion & Best Model

## 🚀 Quick Start
```bash
pip install -r requirements.txt
jupyter notebook ML_Assignment.ipynb
```

- If `data/train.csv` is missing, the notebook will fall back to a **small sample dataset** so you can still see the code structure.  
- After you place the Kaggle file, **re-run the notebook** to update images and results.
