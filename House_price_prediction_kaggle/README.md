
# 🏠 Bengaluru House Price Prediction

This project predicts house prices in Bengaluru using **Machine Learning** techniques. It is based on real-world housing data and involves **data cleaning, feature engineering, model building, and deployment using Flask**.

---

## 📌 **Project Overview**
- Predict house prices in Bengaluru based on features such as:
  - Location
  - Square footage
  - Number of bathrooms
  - BHK (Bedrooms, Hall, Kitchen)
- The model is trained using **Linear Regression** and optimized for better accuracy.
- Deployment is done using **Flask** for API-based predictions.

---

## 📂 **Project Structure**
```
House_price_prediction_kaggle/
│
├── bengaluru_house_price_prediction.ipynb  # Main Jupyter Notebook with full code
├── Bengaluru_House_Data.csv                # Dataset used for training
├── banglore_home_prices_model.pickle       # Trained ML model
├── columns.json                            # Column metadata for prediction
├── Flask_server/                           # Flask app for deployment
│     ├── app.py                            # Flask application script
│     └── templates/                        # HTML files for UI
└── README.md                               # Project documentation
```

---

## ⚙️ **Technologies Used**
- **Python** (pandas, numpy, scikit-learn, matplotlib)
- **Machine Learning** (Linear Regression)
- **Flask** (for model deployment)
- **Pickle** (for model saving and loading)

---

## ✅ **Steps Involved**
1. **Data Cleaning**
   - Handle missing values
   - Remove outliers
2. **Feature Engineering**
   - Convert categorical data into numerical
   - Dimensionality reduction for location features
3. **Model Building**
   - Linear Regression model
   - Performance evaluation using R² score and cross-validation
4. **Model Deployment**
   - Flask API for serving predictions
   - HTML front-end for user input

---

## 🔮 **How to Use**
### 1️⃣ **Run Locally**
Clone the repository:
```bash
git clone https://github.com/your-username/ML_projects.git
cd House_price_prediction_kaggle
```

Install dependencies:
```bash
pip install -r requirements.txt
```

Run Flask server:
```bash
cd Flask_server
python app.py
```

Access the app at:
```
http://127.0.0.1:5000
```

### 2️⃣ **Predict Price**
Enter:
- Location
- Square Foot Area
- Number of Bathrooms
- BHK
Click **Predict** to get the estimated price.

---

## 📊 **Dataset**
- **Source:** Kaggle dataset of Bengaluru House Prices
- **Rows:** ~13,000
- **Columns:** Location, Size, Total Square Feet, Bath, Price, etc.

---

## 📌 **Future Enhancements**
- Add **Random Forest** or **XGBoost** for better accuracy
- Deploy on **Heroku or AWS**
- Add **interactive dashboard** for insights

---

## ✍️ **Author**
**Preta Kumar Binda**  
*Machine Learning Enthusiast | Data Science Learner*  
