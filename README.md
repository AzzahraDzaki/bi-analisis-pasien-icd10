# Healthcare Data BI Project: Inpatient Diagnosis Forecasting and Classification
This project is a Business Intelligence solution designed to help a regional hospital transform its raw patient data into actionable insights. The project uses advanced analytics to predict patient visit trends and diagnose classifications, which supports proactive resource planning and improves service quality.
## About the Project
This project's goal was to address the challenge faced by hospitals in managing patient data. By implementing a structured data pipeline and predictive models, the project turns scattered medical records into a powerful tool for strategic decision-making. The solution focuses on understanding historical patient patterns and forecasting future trends, which enables the hospital to be more proactive in its operations and resource allocation.
## Key Features
1. ETL & Data Warehouse: Developed a comprehensive ETL pipeline to clean, transform, and load raw patient data into a structured star schema for efficient analysis.
2. Time-Series Forecasting: Implemented Prophet models to accurately predict patient visit volumes and the top 5 diagnoses for future periods.
3. Classification Model: Built a robust XGBoost model to classify patient diagnoses based on demographic and administrative features.
4. Interactive Dashboard: Designed a set of Power BI dashboards to visualize key metrics, trends, and model predictions, making complex data easily understandable for stakeholders.

## Technical Stack
1. Programming Language: Python
2. Libraries: pandas, numpy, prophet, scikit-learn, xgboost, matplotlib, seaborn
3. Database: PostgreSQL
4. Tools: Jupyter Notebook, Microsoft Power BI

## Project Structure
This repository is organized into five Jupyter Notebooks that document the entire project pipeline:
1. 1-data-preprocessing-cleaning.ipynb: Initial data cleaning, transformation, and preparation.
2. 2-etl-data-warehouse-modeling.ipynb: Code for building the star schema data warehouse.
3. 3-predictive-analysis-visit-forecasting.ipynb: Prophet model for patient visit forecasting.
4. 4-predictive-analysis-diagnosis-forecasting.ipynb: Prophet model for forecasting diagnosis trends.
5. 5-predictive-analysis-diagnosis-classification.ipynb: XGBoost model for diagnosis classification.
6. requirements.txt: A list of all project dependencies.

## Getting Started
To set up the project environment and run the code, follow these steps:
1. Clone this repository to your local machine.
2. Install all required dependencies by running the following command:

    pip install -r requirements.txt

3. Open the notebooks in Jupyter Notebook or another Python environment.

Note: The raw data files are not included in this repository due to patient data privacy concerns.

## Full Report and Dashboard
For a detailed project narrative, methodology breakdown, and to view the complete interactive dashboards, please visit the full project portfolio on my Notion page.
https://www.notion.so/Dashboard-Analisis-Prediksi-Diagnosis-Pasien-Berbasis-ICD-10-Skripsi-S1-276fc6b6e8b981138a25ce54a682921b?source=copy_link
