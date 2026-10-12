# BDAS Iteration 4
## Predicting Cognitive Performance Using Lifestyle and Wellbeing Indicators
A Big Data Analytics project developed using Google Colab, Apache Spark, PySpark, and Spark MLlib.

This project investigates whether cognitive performance can be predicted using lifestyle and wellbeing indicators through the application of the CRISP-DM methodology and supervised machine learning techniques.

### Project Overview
The objective of this project is to:
- Predict Cognitive Composite Score using lifestyle and wellbeing variables.
- Examine the influence of behavioural factors such as sleep, exercise, stress, and screen time on cognitive performance.
- Demonstrate the application of Big Data Analytics techniques using PySpark and Spark MLlib.
- Evaluate predictive performance using RMSE, MAE, and R² metrics.

### Methodology
The project follows the CRISP-DM framework:

#### 1. Business Understanding
- Defined project objectives and success criteria.
- Identified the relationship between lifestyle factors and cognitive performance.

#### 2. Data Understanding
- Collected and explored two publicly available datasets.
- Performed descriptive statistics and exploratory analysis.

#### 3. Data Preparation
- Cleaned and validated datasets.
- Engineered new features.
- Integrated cognitive and lifestyle datasets.

#### 4. Data Transformation
- Applied data reduction techniques.
- Performed feature transformation and encoding.

#### 5. Modelling
- Developed a Linear Regression model using Spark MLlib.
- Generated predictions using integrated lifestyle and cognitive data.

#### 6. Evaluation
- Evaluated model performance using:
- RMSE
- MAE
- R²
- Compared results across multiple modelling iterations.

### Datasets
- NeuroCognitive Performance Test (NCPT)
- Mental Health Lifestyle Survey 2024

### Dataset Sources
- NCPT Dataset: https://doi.org/10.5281/zenodo.7249732
- Mental Health Lifestyle Survey 2024: https://www.kaggle.com/datasets/kjasmine19/mental-health-lifestyle-survey-2024

### Technologies Used
- Google Colab
- Apache Spark
- PySpark
- Spark MLlib
- Python
- Pandas
- NumPy
- Matplotlib
- GitHub

### Model Evaluation
Metric	Result
- RMSE	9.09
- MAE	6.44
- R²	-0.012

### Academic Purpose
This repository was created as part of the University of Auckland Big Data Analytics coursework. The project demonstrates the application of CRISP-DM methodology, data preparation, feature engineering, predictive modelling, and evaluation using PySpark an Spark MLlib.
