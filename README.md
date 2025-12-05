# 🧠 Diabetes Risk Prediction — Kaggle Playground Series S5E12
### 📌 Machine Learning • Gradient Boosting • LightGBM • Stacking Ensemble  
**Author:** Sajeeb Khan  

![Kaggle](https://img.shields.io/badge/Kaggle-Competition-blue?style=for-the-badge&logo=kaggle)
![Python](https://img.shields.io/badge/Python-3.10+-yellow?style=for-the-badge&logo=python)
![Status](https://img.shields.io/badge/Project%20Status-Active-brightgreen?style=for-the-badge)

---

## 📝 Overview  
This repository contains my full machine learning pipeline for the **Kaggle Playground Series — Season 5, Episode 12** competition.  
The goal is to **predict the diabetes diagnosis (0 or 1)** using tabular health data containing lifestyle, biometric, and medical history features.

I built a clean, optimized ML workflow including:

✔ Exploratory Data Analysis (EDA)  
✔ Correlation heatmap  
✔ Preprocessing (scaling + encoding)  
✔ Multiple ML models  
✔ Gradient Boosting, Random Forest, Logistic Regression  
✔ **LightGBM + Stacking Ensemble (final model)**  
✔ Submission file ready for Kaggle  

---

## 🏆 Kaggle Leaderboard Result  
| Submission | Public Score | Rank | Status |
|-----------|--------------|-------|--------|
| `submission.csv` | **0.62432** | ~756 | ✔ Successfully submitted |

🎉 **Welcome to the leaderboard! This is my first entry in this competition.**

---

## 📂 Repository Structure  
```
├── notebook/
│   └── AIPA_Lite_Diabetes_Competition.ipynb   # Full ML workflow
│
├── submissions/
│   └── submission.csv                         # Final Kaggle submission
│
├── images/                                    # Optional screenshots
│   ├── leaderboard.png
│   └── output.png
│
└── README.md                                  # Documentation
```

---

## 🚀 Features Implemented  
### ✔ Data Handling  
- Missing value checks  
- Label encoding for categorical data  
- Standard scaling for numeric features  

### ✔ Exploratory Data Analysis  
- Distribution plots  
- Heatmap for feature correlations  

### ✔ Machine Learning Models  
| Model | Status |
|-------|--------|
| Logistic Regression | ✔ Tested |
| Random Forest | ✔ Tested |
| Gradient Boosting | ✔ High Performance |
| **LightGBM** | ✔ Best Accuracy |
| **Stacking Ensemble (Final Model)** | ⭐ Chosen model |

---

## 🛠 Installation  
Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/Diabetes-Risk-Prediction-Kaggle.git
cd Diabetes-Risk-Prediction-Kaggle
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## 📊 Final Model Output  
Prediction distribution:

```
1 → 203,899  
0 →  96,101  
```

Submission file head:

```
   id     diagnosed_diabetes
0  700000        0.0
1  700001        1.0
2  700002        1.0
3  700003        0.0
4  700004        1.0
```

---

## 🧠 Key Learnings  
- Ensemble models outperform single models  
- LightGBM handles large tabular datasets efficiently  
- Feature scaling significantly boosts performance  
- Stacking multiple models improves final score  

---

## 🎯 Future Improvements  
- Hyperparameter tuning (Optuna or GridSearch)  
- SHAP interpretability  
- Add CatBoost model  
- Feature engineering for deeper insights  

---

## 🤝 Connect With Me  
🌐 GitHub: https://github.com/sajeebkhan  
📬 Kaggle: https://www.kaggle.com/sajeebkhan  

---  

### ⭐ If you like this project, please give the repository a **star** on GitHub!  
