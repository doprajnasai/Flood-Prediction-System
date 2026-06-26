# Flood Prediction System

## Overview

The Flood Prediction System is a Machine Learning-based web application developed using Python, Flask, and XGBoost. It predicts the likelihood of flooding based on historical weather and rainfall parameters entered by the user.

The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis, feature engineering, model training, model evaluation, and deployment through a Flask web application.

---


## Live Demo

| Resource | Link |
|----------|------|
| **Live Website** | https://flood-prediction-system-3fv8.onrender.com |
| **GitHub Repository** | https://github.com/doprajnasai/Flood-Prediction-System |

---

## Features

- Predicts the likelihood of flood occurrence
- User-friendly Flask web interface
- Real-time prediction using Machine Learning
- Input validation for all weather parameters
- Responsive and modern web design
- XGBoost model integration
- Trained model loaded using Joblib

---

## Machine Learning Workflow

The project follows the complete machine learning pipeline:

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Outlier Detection and Capping
5. Feature Engineering
6. Train-Test Split
7. Feature Scaling using StandardScaler
8. Model Training
9. Model Evaluation
10. Model Selection
11. Model Deployment

---

## Machine Learning Models Used

The following models were trained and evaluated:

| Model | Purpose |
|--------|----------|
| Decision Tree | Classification |
| Random Forest | Classification |
| K-Nearest Neighbors (KNN) | Classification |
| XGBoost | Final Deployed Model |

After evaluating all models, **XGBoost** was selected as the final model due to its superior predictive performance.

---

## Input Features

The prediction model uses the following weather parameters:

| Feature |
|----------|
| Temperature |
| Humidity |
| Cloud Cover |
| Annual Rainfall |
| Jan-Feb Rainfall |
| Mar-May Rainfall |
| Jun-Sep Rainfall |
| Oct-Dec Rainfall |
| Average June Rainfall |
| Subdivision Rainfall |

---

## Prediction Output

The application predicts one of the following results:

- Flood Likely
- No Flood Likely

---

## Technologies Used

### Programming Language

- Python

### Machine Learning

- Scikit-learn
- XGBoost
- Joblib

### Data Analysis

- Pandas
- NumPy

### Data Visualization

- Matplotlib
- Seaborn

### Web Framework

- Flask

### Frontend

- HTML
- CSS

### Deployment

- Render

---

## Project Structure


## Project Structure

```text
Flood-Prediction-System/
│
├── app.py
├── Procfile
├── requirements.txt
├── README.md
├── .gitignore
│
├── dataset/
│   └── flood_dataset.xlsx
│
├── notebooks/
│   └── Flood_Prediction.ipynb
│
├── saved_models/
│   ├── flood_model.joblib
│   └── scaler.joblib
│
├── static/
│   ├── css/
│   │   └── style.css
│   │
│   └── images/
│       └── flood.jpg
│
├── templates/
    ├── index.html
    └── predict.html

```


---

## Installation

### Clone the repository


git clone https://github.com/doprajnasai/Flood-Prediction-System.git


### Navigate to the project directory


cd Flood-Prediction-System


### Create a virtual environment


python -m venv venv


### Activate the virtual environment

#### Windows


venv\Scripts\activate


#### Linux / macOS


source venv/bin/activate


### Install dependencies


pip install -r requirements.txt


### Run the Flask application


python app.py


Open your browser and visit:


http://127.0.0.1:5000


---


## Future Enhancements

- Integration with live weather APIs
- Location-based flood prediction
- Interactive flood risk maps
- Rainfall trend visualization
- Deep Learning implementation
- Mobile application support

---

## Developer

**Doprajna Sai Vadlamudi**

B.Tech Computer Science and Engineering

SRM University AP

---

## License

This project is developed for educational and academic purposes only.
