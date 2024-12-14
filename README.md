# 🏏 IPL Score Predictor

## 🌟 Overview
This Streamlit web app enables users to predict total runs scored between teams using current runs and wickets. It leverages machine learning algorithms for precise predictions.

## ✨ Features
- 🔢 Predict total runs based on live match data.
- 🤖 Algorithms include Linear Regression, K-Nearest Neighbor Regressor, XGBoost Regressor, Random Forest Regressor, SVR, and Decision Tree Regressor.
- ⚙️ Hyperparameter optimization using Optuna for improved model performance.
- 🌐 Interactive web app built with Streamlit.

## 🛠 Technologies Used
- **Programming Language:** Python
- **Libraries and Frameworks:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn, Streamlit

## 📊 Dataset
The dataset comprises ball-by-ball details of IPL matches from 2008 to 2020.

### 🗂 Dataset Used: `ipl_data.csv`
#### 📋 Columns:
- `mid`: Match ID
- `date`: Match date
- `venue`: Match venue
- `bat_team`: Batting team
- `bowl_team`: Bowling team
- `batsman`: Batsman
- `bowler`: Bowler
- `runs`: Runs scored
- `wickets`: Wickets lost
- `overs`: Overs completed
- `run_last_5`: Runs scored in the last 5 overs
- `wicket_last_5`: Wickets lost in the last 5 overs
- `striker`: Current batsman
- `non-striker`: Supporting batsman
- `total`: Total score (target variable)

## 🖥 Prerequisites
- 🐍 Python 3.7 or higher

### 📦 Required Python Libraries:
Install the required libraries by running:
```bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn
```

## 🚀 Getting Started
### 📥 Clone the Repository:
```bash
git clone https://github.com/srikrishna719/ipl-score-predictor.git
```

## 🛠 Usage
1. **📤 Upload the Dataset:** Ensure the dataset (`ipl_data.csv`) is in the project directory.
2. **✍️ Input Current Match Data:** Provide details like runs, wickets, and overs completed.
3. **📈 Get Predictions:** View predicted total runs for the match.

## 📚 Algorithms Used
- 📏 Linear Regression
- 👥 K-Nearest Neighbor Regressor
- 🚀 XGBoost Regressor
- 🌲 Random Forest Regressor
- 🔄 SVR
- 🌳 Decision Tree Regressor

## 🎛 Hyperparameter Optimization
Optuna was used for parameter optimization, ensuring better accuracy and performance.

## 🏆 Results
- ✅ Accurate predictions for total runs based on historical match data.
- 📊 Insights into how various factors like team performance and match conditions influence scores.

## 🙏 Acknowledgments
- 📂 The IPL dataset was obtained from publicly available cricket databases.
- 🧠 Inspired by cricket analytics and real-time match predictions.

---

🎉 *Happy predicting!*
