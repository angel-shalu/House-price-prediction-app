# 🏡 House Price Prediction

This project demonstrates House Price Prediction using Simple Linear Regression and Multiple Linear Regression.
The goal is to predict house prices based on features such as square feet (sqft living), floors, bedrooms, and other attributes.

The app is built using Python, Scikit-learn, and Streamlit, and the models are saved using Pickle for deployment.

📌 Features

✅ Simple Linear Regression – Predicts price using only sqft_living
✅ Multiple Linear Regression – Uses multiple features like sqft_living, floors, bedrooms, etc.
✅ Interactive Streamlit App for real-time predictions
✅ Models saved and loaded with Pickle
✅ Easy-to-use interface for users

⚙️ Tech Stack

Python 🐍

Numpy & Pandas → Data manipulation

Matplotlib & Seaborn → Data visualization

Scikit-learn → Machine Learning (Linear Regression)

Pickle → Model saving/loading

Streamlit → Web app

📂 Project Structure
House_Price_Prediction/
│
├── data/
│   └── House_data.csv               # Dataset
│
├── models/
│   ├── simple_linear_model.pkl      # Saved Simple Linear Regression model
│   └── multiple_linear_model.pkl    # Saved Multiple Linear Regression model
│
├── notebooks/
│   ├── simple_linear_regression.ipynb
│   └── multiple_linear_regression.ipynb
│
├── app.py                           # Streamlit app
├── requirements.txt                 # Dependencies
└── README.md                        # Project documentation

🚀 How to Run
1. Clone the Repository
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction

2. Install Dependencies
pip install -r requirements.txt

3. Run the Streamlit App
streamlit run app.py

📊 Model Information
🔹 Simple Linear Regression

Feature used: sqft_living


🔹 Multiple Linear Regression

Features used: sqft_living, floors, bedrooms, bathrooms, etc.


✨ Example Predictions
✅ Simple Linear Regression

Input: sqft_living = 2000

Output: Predicted Price ≈ ₹ 50,00,000

✅ Multiple Linear Regression

Input: sqft_living = 2000, floors = 2, bedrooms = 3, bathrooms = 2

Output: Predicted Price ≈ ₹ 62,00,000

🙌 Acknowledgements

This project was developed as part of my Data Science learning journey.
