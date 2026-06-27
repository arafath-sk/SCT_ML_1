# SCT_ML_1
# 🤖 SkillCraft Technology — Machine Learning Internship
## 📌 Task 1 — House Price Prediction

### 🎯 Objective
Build a machine learning model to predict the sale price of houses based on features like size, quality, location, and more.

### 📂 Dataset
- **Source:** [Kaggle — House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)
- **Training data:** 1,460 houses with 80 features
- **Test data:** 1,459 houses

### 🛠️ Tools & Technologies
- **Language:** Python 3.11
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Environment:** Jupyter Notebook (VS Code)

### 🔄 Process
1. **Data Exploration (EDA)** — Analyzed distributions, correlations, and missing values
2. **Data Cleaning** — Handled missing values, dropped low-quality columns
3. **Feature Engineering** — Created new features like TotalSF, HouseAge, TotalBaths
4. **Encoding** — Converted categorical columns using One-Hot Encoding
5. **Model Training** — Trained and compared 3 models:
   - Linear Regression
   - Random Forest Regressor
   - Gradient Boosting Regressor
6. **Evaluation** — Used 5-fold Cross Validation and RMSE scoring
7. **Prediction** — Generated final predictions on test data

### 📊 Results
| Model | RMSE Score |
|-------|-----------|
| Linear Regression | ~0.15 |
| Random Forest | ~0.14 |
| Gradient Boosting | ~0.12 ✅ Best |

### 📁 Files
| File | Description |
|------|-------------|
| `house_price_prediction.ipynb` | Complete Jupyter Notebook with code and charts |
| `submission.csv` | Final predicted house prices |

---

## 📌 Task 2 — Customer Segmentation (Coming Soon)
K-means clustering to group retail store customers based on purchase history.

---

## 🙋 About Me
**Intern at SkillCraft Technology**
Connect with me on [LinkedIn](#) <!-- paste your LinkedIn URL here -->

---

⭐ If you found this helpful, feel free to star this repository!
