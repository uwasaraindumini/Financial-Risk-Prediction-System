# Financial-Risk-Prediction-System

📋 Overview
The Financial Risk Prediction System is a machine learning-powered application designed to classify individuals into financial risk categories (High, Medium, Low) based on their demographic, financial, and behavioral data. This project leverages advanced machine learning techniques to provide financial institutions with actionable insights, enabling better lending decisions and risk management.

Deployed Application: Streamlit App

🚀 Key Features
1️⃣ Data Cleaning & Preprocessing
    Treated missing values using stratified median imputation.
    Addressed class imbalance with ADASYN (Adaptive Synthetic Sampling).
    Converted categorical data into numerical format using OrdinalEncoder and LabelEncoder.
2️⃣ Feature Scaling & Selection
    Scaled numerical features with MaxAbsScaler to standardize data.
    Identified critical features using Mutual Information (MI) scores, optimizing the dataset for training.
3️⃣ Model Training & Evaluation
    Trained and evaluated XGBoost, CatBoost, LightGBM, and RandomForest models.
    Fine-tuned hyperparameters using RandomizedSearchCV and GridSearchCV to enhance performance.
    Selected XGBoost as the best-performing model for deployment.
4️⃣ Deployment
    Deployed the application with a Streamlit interface, providing real-time predictions.
    Saved the trained model, encoders, and scalers as Pickle files for easy reuse.

📊 Project Workflow
    Data cleaning and preprocessing to prepare the dataset.
    Feature engineering and selection for optimized training.
    Model training, evaluation, and hyperparameter tuning.
    Deployment of the final model with a user-friendly Streamlit interface.

🔧 Tools & Technologies
    Languages: Python
    Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost, CatBoost, LightGBM
    Frameworks: Streamlit
    Version Control: GitHub

🎯 Goals & Impact
    This system empowers financial institutions to:
        Accurately predict financial risk, reducing defaults.
        Automate risk assessments for faster decision-making.
        Enhance transparency and trust through Explainable AI.

👥 Team Members
    Eshanie Rathnasinghe
    Thiyara Gunawardena
    Binuki Mihara
    Chathuni Abesinghe

📂 Repository Structure
    app.py: Streamlit application code.
    model.pkl: Saved XGBoost model.
    preprocessing.pkl: Encoders and scalers for preprocessing.
    data/: Dataset files and preprocessing scripts.
    notebooks/: Jupyter notebooks for model training and evaluation.

📌 Links
    Deployed Application: Streamlit App
    Dataset: Kaggle - Financial Risk Dataset

🔗 License
This project is licensed under the MIT License. See the LICENSE file for details.

Feel free to explore, contribute, and share your thoughts! 😊
