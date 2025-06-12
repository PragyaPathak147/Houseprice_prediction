# 🏠 House Price Prediction using Machine Learning

A complete end-to-end regression pipeline built to predict house prices based on features such as location, number of rooms, square footage, and more.

---

## 📊 Dataset
The dataset contains residential property features like:
- `bedrooms`, `bathrooms`, `sqft_living`, `lat`, `long`
- `city`, `statezip`
- `yr_built`, `price` (target)

---

## 🧼 Data Preprocessing
- **Outlier Removal** using IQR (Interquartile Range)
- **Missing Value Handling**
- **OneHotEncoding** for categorical variables (`city`, `statezip`)
- **StandardScaler** for numerical features

---

## 🧠 Models Used
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor (with GridSearchCV)
- Support Vector Regressor (SVR) with RBF & Linear kernels
- Gradient Boosting Regressor
- XGBoost Regressor (with RandomizedSearchCV)

---

## 🔍 Model Evaluation
Metrics used:
- R² Score
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)

**Best Model Achieved**:  
📈 **XGBoost Regressor** with R² ≈ 0.64 after hyperparameter tuning.

---

## 🔁 Pipeline Architecture
Built with `scikit-learn` Pipelines & `ColumnTransformer` to ensure:
- Consistent preprocessing
- No data leakage
- Easy experimentation

---

## 📎 Tools & Libraries
- Python, Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn (for EDA & visualization)

---

## 🚀 How to Run
1. Clone this repo
2. Install requirements: `pip install -r requirements.txt`
3. Run notebook `house-price-detection.ipynb`

---

## 📌 Author
**Pragya Pathak**  
_IIT Kharagpur | Economics + Data Science Enthusiast_  
