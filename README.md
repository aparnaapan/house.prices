House Price Prediction App 🏡

This is a simple web application that predicts house prices based on the area (in sq. ft.) using Linear Regression. The app is built with Python, developed in Jupyter Notebook, and deployed using Streamlit.

Features

Predicts house prices from user-input area (sq. ft.)

Interactive Streamlit UI for easy use

Uses a linear regression model for prediction

Quick and beginner-friendly project to showcase ML deployment

Dataset

The dataset contains house prices along with their corresponding areas (in square feet).

Only single-variable linear regression is used for this project (Area → Price).

Data preprocessing and model training are done in Python (Jupyter Notebook).

How to Use

Clone this repository:

git clone <repository_url>


Navigate to the project directory:

cd house-price-app


Install dependencies:

pip install -r requirements.txt


Run the Streamlit app:

streamlit run app.py


Enter the area (sq. ft.) of the house in the input box and get the estimated house price.

Technologies Used

Python – For model building and data handling

Pandas & NumPy – Data manipulation

Scikit-learn – Linear regression model

Joblib – Saving and loading the trained model

Streamlit – Web app UI and deployment

Matplotlib & Seaborn – (Optional) Data visualization

Project Structure
house-price-app/
│
├── app.py                # Streamlit app code
├── model.pkl             # Trained Linear Regression model
├── data.csv              # Dataset used for training
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation

Deployment

The app is deployed on Streamlit Cloud.

Users can access it via a public URL and predict house prices without installing anything locally.

Future Improvements

Add multiple features like number of bedrooms, bathrooms, location, etc.

Improve model accuracy using multiple regression or other algorithms

Add data visualizations to explore price trends
