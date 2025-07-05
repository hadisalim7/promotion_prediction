## 🎯 Problem Statement

The task is to predict whether an employee will be promoted or not using demographic and performance data. The dataset is from the WNS Analytics Wizard 2018 hackathon on Analytics Vi

## ⚙️ Approach

- Handled missing values (`education`, `previous_year_rating`)
- Label encoded categorical features
- Trained 3 models:
  - Logistic Regression → F1 Score: 0.13
  - Random Forest → F1 Score: 0.42
  - **XGBoost** → ✅ **Best F1 Score: 0.51**
- Final predictions made with XGBoost

## 📈 Results

- **Public Leaderboard F1 Score:** `0.4796`
- **Leaderboard Rank:** `#1805`

## 📄 Files Included

- `promotion_prediction.ipynb` – Final notebook
- `submission.csv` – Final prediction file
- `submission_score.png` – Screenshot of leaderboard score
