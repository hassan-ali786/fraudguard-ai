# Fraud Detection using Machine Learning

A machine learning project that detects fraudulent credit card transactions using a highly imbalanced dataset.  
The project focuses on precision-recall evaluation and highlights real-world trade-offs in fraud detection.

---

## Video Demo

<video src="https://github.com/user-attachments/assets/ce78b163-c052-4ab6-bfeb-622dee15d6ab" width="100%" controls></video>

---

## Project Overview

This project predicts fraudulent transactions:

- Handle class imbalance in credit card transaction data  
- Train and evaluate classification models  
- Focus on **precision** and **recall** rather than accuracy  
- Analyze trade-offs between false positives and false negatives  

---

## Dataset Information

- **Source:** Kaggle – Credit Card Fraud Detection Dataset  
- **Features:**  
  - Time  
  - Amount  
  - PCA-transformed anonymized features (V1–V28)  
- **Target:** Class  
  - `0` → Legit  
  - `1` → Fraud  

---

## Tools & Technology Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-007D9C?style=flat&logo=matplotlib&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

## Methodology

1. Analyze class imbalance and data distribution  
2. Apply stratified train-test split  
3. Use class weighting for imbalanced data  
4. Train models:  
   - Logistic Regression  
   - Random Forest Classifier  
5. Evaluate models using **Precision**, **Recall**, and **F1-score**  

---

## Trade-offs Discussion

- **Accuracy** is misleading for imbalanced datasets  
- **Precision** reduces false fraud alerts  
- **Recall** ensures fraudulent transactions are detected  
- Logistic Regression is interpretable  
- Random Forest captures complex patterns but is less explainable  

---

## Project Structure

```bash
fraudguard-ai/
├── notebooks/
│   └── Fraud_Detection_Imbalanced_Data.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/hassan-ali786/fraudguard-ai
cd fraud-detection-imbalanced-data
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Download the dataset from Kaggle (`creditcard.csv`) and place it in the `data/` folder  

4. Open and run the notebook:

```bash
jupyter notebook notebooks/Fraud_Detection_Imbalanced_Data.ipynb
```

5. Run all cells to reproduce analysis, model training, and evaluation  

---

## Key Learnings

- Handling imbalanced datasets effectively  
- Understanding precision-recall trade-offs in fraud detection  
- Comparison of Logistic Regression vs Random Forest for classification  
- Evaluating models beyond accuracy using business-critical metrics  

---

## Future Improvements

- Experiment with XGBoost and LightGBM for better performance  
- Implement anomaly detection techniques for fraud  
- Deploy a real-time fraud detection web app  
- Visualize feature importance and transaction patterns  

---

## Author

**Hassan Ali**  
Data Scientist & ML Engineer  

---

