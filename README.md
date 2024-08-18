# Heart Disease Prediction

# Overview
The Heart Disease Prediction project is a web-based application that leverages machine learning algorithms to predict the likelihood of heart disease in patients. This application aims to assist healthcare professionals by providing quick and accurate predictions. The project utilizes Flask for the backend, NumPy for data manipulation, and Pickle for model serialization. Additionally, the application includes a user authentication system with login and signup pages, built using HTML, CSS, and JavaScript.

# Features
- Multiple Machine Learning Algorithms: Incorporates various algorithms to improve the accuracy of heart disease predictions.
- User Authentication: Secure login and signup functionality to protect user data.
- Data Input: Allows users to input patient data for prediction.
- Prediction Output: Provides a probability score indicating the likelihood of heart disease.
- User-Friendly Interface: Intuitive web interface for easy data input and viewing results.

# Technologies Used
- Python: Core programming language used for the application.
- Flask: Framework for building the web application and managing server-side logic.
- NumPy: Library for efficient data manipulation and numerical operations.
- Pickle: Used for serializing and deserializing the machine learning models.
- HTML/CSS/JavaScript: Frontend technologies for building the user interface.
- Scikit-learn: Machine learning library used to develop and train predictive models.

# Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/heart-disease-prediction.git
   cd heart-disease-prediction

   python -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`

pip install -r requirements.txt

python app.py

