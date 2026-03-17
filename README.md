# 💳 Credit Card Fraud Detection System

## 📌 Overview
A machine learning system to detect fraudulent 
credit card transactions using XGBoost classifier 
with GPU acceleration on Google Colab.

## 📊 Results
| Metric     | Score  |
|------------|--------|
| ROC-AUC    | 97.50% |
| Precision  | 95.83% |
| Recall     | 83.13% |
| F1 Score   | 89.03% |

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost (GPU accelerated)
- SMOTE (imbalanced data handling)
- SHAP (model explainability)
- Google Colab (T4 GPU)

## 📁 Dataset
- 284,807 transactions
- Only 492 fraud cases (0.17%)
- Source: Kaggle Credit Card Fraud Detection

## 🚀 How to Run
1. Open Fraud_Detection.ipynb in Google Colab
2. Upload creditcard.csv dataset
3. Enable T4 GPU runtime
4. Run all cells in order

## 📈 Key Achievements
- Handled severely imbalanced dataset using SMOTE
- Used XGBoost with GPU acceleration
- Generated model explanations using SHAP
- Achieved 97.50% ROC-AUC score
- Precision above 90% project goal

## 📂 Project Structure
- Fraud_Detection.ipynb → Main notebook
- README.md → Project description
