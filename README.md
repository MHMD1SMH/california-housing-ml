# California Housing Price Prediction

## 📌 Objective
The goal of this project is to build a machine learning model to predict housing prices in California using the **California Housing dataset**.  
We focused on data preprocessing, exploratory data analysis (EDA), and training multiple regression models.

---

## 📂 Dataset
- **File**: `housing.csv`  
- Contains information about California districts, including features like:
  - Median income
  - Total rooms
  - Total bedrooms
  - Population
  - Households
  - Latitude, Longitude
  - Ocean proximity

---

## 🔎 Exploratory Data Analysis & Preprocessing
1. **Checked missing values** → imputed `total_bedrooms` using the median.  
2. **Explored correlations** → heatmap of numerical features.  
3. **Handled categorical feature**: `ocean_proximity` (encoded for ML).  
---

## 🤖 Models Used
We trained and evaluated several models:
- **Linear Regression**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- **XGBoost Regressor**

---

## 📊 Results
- The models achieved an **R² score ≈ 0.83** on the test set.  
- This means the model explains ~82% of the variance in housing prices.  
- **Feature Importance (XGBoost)** showed that:
  - Median income is the most important predictor.
  - Location features (latitude, longitude) are also highly influential.

---

## 🚀 How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/california-housing-ml.git
   cd california-housing-ml
