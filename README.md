🩺 Breast Cancer Prediction Web App

This project is a machine learning-powered web application developed using Streamlit that predicts whether a tumor is benign or malignant based on clinical and diagnostic features.

📌 Features

* Predicts tumor type using medical features such as:

  * Radius Mean
  * Texture Mean
  * Perimeter Mean
  * Area Mean
  * Smoothness Mean
  * ...and other important attributes
* Takes user input via interactive sidebar sliders
* Displays real-time prediction result (Benign / Malignant)
* Built-in model trained on a real-world breast cancer dataset
* Simple, responsive UI for healthcare use-cases or educational demos

💡 Technologies Used

* Python, Pandas, NumPy, Scikit-learn
* Streamlit for web UI
* Pickle for model deployment

📁 Project Files

* Breast_Cancer_Prediction.ipynb: Jupyter Notebook for model training and evaluation
* app.py: Streamlit web app code
  best_model_name.pkl: Trained classifier model
* Breast Cancer Prediction.csv: Dataset used (likely from UCI or similar)
