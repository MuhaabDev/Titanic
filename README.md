---
# 🚢 Titanic - Kaggle Competition

Yes… it’s **that Titanic competition**.
The one every beginner touches at some point.
And here I am—joining the 1.4 million+ entrants, hoping to learn, improve, and climb the leaderboard.

---

## 📊 Participation Stats (as of now)

* **Entrants:** 1,404,227
* **Participants:** 13,708
* **Teams:** 13,683
* **Total Submissions:** 47,416

---

## 🏆 My Progress So Far

| Version | Train Accuracy | Test Accuracy | Rank   |
| ------- | -------------- | ------------- | ------ |
| V4      | 78%            | 74%           | 10,395 |
| V7      | 84%            | 77%           | 8,862  |

💡 Each new version I’ll keep refining features, tuning models, and pushing updates here.

---

## 📂 Project Workflow

1. **Load the Data**

   * Import datasets (`train.csv`, `test.csv`).
   * Basic sanity checks and cleanup.

2. **Explore and Visualize the Data**

   * Checked survival distributions across features (sex, age, class, etc).
   * Plotted correlations and survival trends.

3. **Feature Engineering**

   * Extracted titles from names.
   * Engineered family size.
   * Binned age and fare.
   * Encoded categorical features.

4. **Pipeline Setup**

   * Built a scikit-learn pipeline for preprocessing + model training.

5. **Training & Validation**

   * Started with baseline Logistic Regression → then RandomForest → tuned towards XGBoost.
   * Cross-validation for stability.

6. **Fine Tuning (RandomizedSearchCV)**

   * Ran randomized search on hyperparameters to squeeze out extra performance.

---

## 🚀 Next Steps

* Try feature scaling & interactions.
* Experiment with Gradient Boosting + Ensemble methods.
* Dive into feature selection.
* Aim for < 5k rank.

---

## ⚡ Takeaway

This repo is my learning log.
Not about being #1 (yet), but about **getting better each iteration**.
Stay tuned for updates!

---
