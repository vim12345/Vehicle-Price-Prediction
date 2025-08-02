# Vehicle-Price-Prediction

# 📌 Project Overview
* This project predicts the price of vehicles based on various attributes such as make, model, year, mileage, engine details, and more.
* It uses machine learning techniques—specifically the XGBoost Regressor—to estimate vehicle prices accurately.

# 📊 Dataset
# The dataset includes:

Make (e.g., Toyota, Ford)

Model

Year

Mileage

Engine

Fuel type

Transmission

Trim

Body style

Color (interior & exterior)

Drivetrain

Price (target variable)

# ⚙️ Installation
Make sure Python 3.7+ is installed.

# Install the required libraries using:

pip install pandas numpy scikit-learn xgboost matplotlib seaborn
# ▶️ How to Run
Place dataset.csv and predict_vehicle_price.py in the same directory.

# Run the script using:


python predict_vehicle_price.py
# The script will output:

RMSE and R² Score

A feature importance plot saved as feature_importance.png

# 🧠 Model Info
**Model:** XGBoost Regressor

**Hyperparameters:**

n_estimators = 100

learning_rate = 0.1

max_depth = 6

random_state = 42

# 📤 Output
Printed performance metrics (RMSE, R²)

Feature importance visualization: feature_importance

# ✍️ Author
Prepared for project submission by Vimal Kumar

