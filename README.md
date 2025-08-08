# 🚜 Bulldozer Price Prediction (Kaggle)

This project builds an **end-to-end machine learning pipeline** to predict the **sale price of used bulldozers** using historical sales data from the *Bluebook for Bulldozers* Kaggle competition.  
The workflow covers **data preprocessing, feature engineering, model training, evaluation, and insights extraction**.

---

## 🎯 Objective
Predict bulldozer auction prices based on historical attributes such as:
- **Sale date**
- **Machine age**
- **Usage type**
- **Product class**
- And other relevant features

---

## 📊 Tools & Technologies
- **Languages/Libraries:** Python, Pandas, NumPy, Matplotlib, Scikit-learn  
- **Environment:** Jupyter Notebook  

---

## 🧮 Dataset
- **Source:** [Kaggle - Bluebook for Bulldozers](https://www.kaggle.com/competitions/bluebook-for-bulldozers)  
- **Description:** Historical sales records of bulldozers including product specifications, usage, and sale prices.

---

## 🏆 Evaluation Metric
- **Root Mean Squared Logarithmic Error (RMSLE)**
- Achieved **Validation RMSLE ≈ 0.24**

---

## 🧠 Key Techniques
- Extracted features from datetime columns  
- Handled missing values and categorical encoding  
- Implemented **Random Forest Regressor** for prediction  
- Performed hyperparameter tuning for improved accuracy  
- Analyzed feature importance and error distribution

---

## 📈 Model
- **Algorithm:** Random Forest Regressor
- **Performance:** RMSLE ≈ 0.24 on validation set

---

## 📂 Project Structure
├── data/ # Dataset files (if available)
├── notebooks/ # Jupyter notebooks for analysis & modeling
├── src/ # Python scripts (data processing, modeling)
├── README.md # Project documentation
└── requirements.txt # Required Python packages


---

## 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/your-username/bulldozer-price-prediction.git
cd bulldozer-price-prediction

# Install dependencies
pip install -r requirements.txt

# Open Jupyter Notebook
jupyter notebook

📌 Results & Insights
Seasonal patterns observed in auction prices
Machine age and usage type were top predictors of sale price
Feature engineering significantly improved model accuracy

📜 License
This project is for educational purposes based on the Kaggle competition dataset.


