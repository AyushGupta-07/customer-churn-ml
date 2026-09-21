
# Customer Churn Prediction & Analysis

An end-to-end machine learning project for analyzing customer churn, training classification models, evaluating their performance, and presenting insights through an interactive Streamlit dashboard.

## Project Overview

Customer churn is an important business problem where companies need to identify customers who are likely to discontinue their services.

This project demonstrates a complete machine learning workflow:

- Data generation and preprocessing
- Exploratory data analysis
- SQL-based data analysis
- Feature engineering
- Machine learning model training
- Model evaluation
- Feature importance analysis
- Interactive Streamlit dashboard
- FastAPI prediction API
- Docker-based deployment setup

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- SQL / SQLite
- Matplotlib
- Seaborn
- Streamlit
- FastAPI
- Docker

## Machine Learning Models

The project uses multiple classification algorithms:

1. Logistic Regression
2. Random Forest
3. XGBoost

Models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

## Project Workflow

```text
Customer Data
      ↓
Data Preprocessing
      ↓
Exploratory Data Analysis
      ↓
Feature Engineering
      ↓
Train/Test Split
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Feature Importance
      ↓
Churn Prediction
      ↓
Streamlit Dashboard / FastAPI
````

## Dashboard

The Streamlit dashboard provides visual analysis of:

* Customer churn distribution
* Contract type and churn
* Customer tenure
* Monthly charges
* Feature relationships
* Model performance
* Feature importance

## Project Structure

```text
customer-churn-ml/
│
├── app/
│   ├── api.py
│   └── streamlit_app.py
│
├── data/
│   └── customer_churn_db.sqlite
│
├── models/
│   ├── best_model.pkl
│   ├── logistic_regression.pkl
│   └── preprocessing_artifacts.pkl
│
├── plots/
│   ├── churn_distribution.png
│   ├── confusion_matrices.png
│   ├── contract_type_analysis.png
│   ├── correlation_heatmap.png
│   ├── feature_importance.png
│   ├── monthly_charges_vs_churn.png
│   ├── roc_curves.png
│   └── tenure_vs_churn.png
│
├── sql/
├── src/
├── deploy/
├── main.py
├── Dockerfile
├── docker-compose.yml
├── requirements.txt
└── README.md
```

## Running the Project Locally

### 1. Clone the repository

```bash
git clone https://github.com/AyushGupta-07/customer-churn-ml.git
cd customer-churn-ml
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the ML pipeline

```bash
python main.py
```

### 4. Launch the Streamlit dashboard

```bash
streamlit run app/streamlit_app.py
```

The dashboard will be available at:

```text
http://localhost:8501
```

## API

The project also includes a FastAPI application for serving predictions.

Run:

```bash
uvicorn app.api:app --reload
```

API documentation:

```text
http://127.0.0.1:8000/docs
```

## Docker

The project includes Docker configuration for containerized execution.

```bash
docker-compose up --build
```

## Key Learning Outcomes

Through this project, I worked with:

* End-to-end ML workflow
* Classification algorithms
* Model evaluation and comparison
* Feature engineering
* SQL data analysis
* Data visualization
* Model persistence
* Streamlit application development
* FastAPI
* Docker

## Attribution

This project is an adapted learning implementation.
The implementation was used for learning and portfolio development, with the project structure and components reviewed and executed locally.

## Author

**Ayush Gupta**

GitHub:
[https://github.com/AyushGupta-07](https://github.com/AyushGupta-07)

