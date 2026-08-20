# Salary Prediction using Machine Learning

This project is a machine learning-based Salary Prediction application developed as part of the **30-hour Certificate Course in Advanced Machine Learning Using Python**, offered by **Cinute Digital Pvt. Ltd. in collaboration with Bhavan's college**.

The project focuses on predicting salary based on factors such as age, gender, education level, job title, and years of experience.

## Dataset

The dataset contains **390 records and 6 features**:

- Age
- Gender
- Education Level
- Job Title
- Years of Experience
- Salary

Data cleaning, exploratory data analysis (EDA), and visualization were performed before model training.

## Machine Learning Workflow

The project follows these steps:

1. Data loading and exploration
2. Data cleaning and preprocessing
3. Exploratory Data Analysis (EDA)
4. Data visualization
5. Train-test split (80% training, 20% testing)
6. Model selection and comparison
7. Model training
8. Model evaluation
9. Feature importance analysis
10. Model and encoder saving
11. Streamlit deployment

## Models Used

The following machine learning models were explored:

- Linear Regression
- Decision Tree
- Random Forest
- XGBoost
- K-Nearest Neighbors (KNN)

After comparing the models, **Random Forest** was selected as the best-performing model for this dataset.

## Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

Feature importance was also visualized to understand the contribution of different features to the Random Forest model.

## Deployment

The trained model and Label Encoders were saved using **Joblib**.

The prediction application was developed using **Streamlit** and deployed as a web application.

### Files in this Repository

- `app.py` – Streamlit application
- `salary_prediction_model.pkl` – Trained Random Forest model
- `label_encoder.pkl` – Saved Label Encoders
- `requirements.txt` – Required Python libraries
- `README.md` – Project documentation

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib
- Streamlit
- GitHub

## Live Application

**Streamlit App:**  
https://salary-prediction-shruts.streamlit.app/#salary-prediction

## Learning Outcome

This project provided hands-on experience with the complete machine learning workflow, from **data preparation and exploratory analysis to model selection, evaluation and deployment**.


<img width="2171" height="1508" alt="Screenshot 2026-08-20 195650" src="https://github.com/user-attachments/assets/06b02fd3-8e8b-4c32-800d-359c0ed2cb5a" />
