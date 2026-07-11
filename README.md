#  Bike Rental Demand Prediction

##  Project Overview

This project aims to predict the daily number of rented bicycles using machine learning regression models. The notebook covers the complete machine learning workflow, including data exploration, preprocessing, model training, hyperparameter optimization, evaluation, and model interpretation.

##  Dataset

The project uses the **Bike Sharing Dataset**, which contains daily records of bicycle rentals along with weather conditions, seasonal information, and calendar-related features.

**Target variable:**

* `cnt` – total number of rented bikes per day.

##  Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* LightGBM
* Optuna
* SHAP

##  Project Workflow

* Exploratory Data Analysis (EDA)
* Data preprocessing
* Feature engineering
* Pipeline construction
* Model training
* Hyperparameter tuning with Optuna
* Model evaluation
* Model comparison
* Feature importance analysis using SHAP

##  Models

The following regression models were trained and compared:

* Random Forest Regressor
* LightGBM Regressor

Hyperparameters were optimized using **Optuna**.

##  Evaluation Metrics

The models were evaluated using:

* R2 Score

##  Model Interpretation

SHAP was used to explain model predictions and identify the most influential features affecting bike rental demand.

##  Repository Structure

```text
.
├── bikes.ipynb
├── day.csv
├── requirements.txt
└── README.md
```

##  How to Run

1. Clone the repository.
2. Install the required packages:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook bikes.ipynb
```

or use Google Colab.

##  Results

* Performed a complete exploratory data analysis.
* Built a preprocessing pipeline.
* Trained and compared Random Forest and LightGBM models.
* Optimized model hyperparameters using Optuna.
* Interpreted model predictions using SHAP.
* Identified the most important factors influencing bike rental demand.

##  Author

**Aryna Kachaharava**

