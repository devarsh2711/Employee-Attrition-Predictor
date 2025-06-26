
# Employee Attrition Prediction

## Overview

This project aims to predict employee attrition using a dataset with over 30 attributes related to employee demographics, job roles, and performance metrics. The objective is to develop a predictive model to identify employees who are likely to leave the company. The project includes exploratory data analysis, data cleaning, model training, and deployment using Streamlit.

## Project Structure

- `app.py`: Main Streamlit application to serve the model.
- `model.py`: Contains the code to train and evaluate the predictive model.
- `data/`: Directory containing the dataset files.
- `requirements.txt`: Python package dependencies for the project.
- `README.md`: This file.

## Dependencies

This project requires the following Python packages:

```plaintext
Flask==1.1.1
gunicorn==19.9.0
itsdangerous==1.1.0
Jinja2==2.10.1
MarkupSafe==1.1.1
Werkzeug==0.15.5
numpy>=1.9.2
scipy>=0.15.1
scikit-learn>=0.18
matplotlib>=1.4.3
pandas>=0.19
streamlit>=0.84.0
```
Install the dependencies using pip:
```
pip install -r requirements.txt
```
Dataset

The dataset used in this project contains the following column:
```
    Id: Unique identifier for each employee
    Age: Age of the employee
    Attrition: Whether the employee has left the company (1) or not (0)
    BusinessTravel: Frequency of business travel (e.g., Non-Travel, Travel_Rarely)
    Department: Department where the employee works
    DistanceFromHome: Distance of the employee's home from the workplace
    Education: Level of education of the employee
    EducationField: Field of education
    EmployeeNumber: Unique employee number
    EnvironmentSatisfaction: Satisfaction with the work environment
    Gender: Gender of the employee
    JobInvolvement: Level of job involvement
    JobRole: Role of the employee in the company
    JobSatisfaction: Level of job satisfaction
    MaritalStatus: Marital status of the employee
    MonthlyIncome: Monthly income of the employee
    NumCompaniesWorked: Number of companies the employee has worked for
    OverTime: Whether the employee works overtime (Yes/No)
    PercentSalaryHike: Percentage increase in salary
    PerformanceRating: Performance rating of the employee
    StockOptionLevel: Level of stock options
    TotalWorkingYears: Total number of years the employee has worked
    TrainingTimesLastYear: Number of training times last year
    YearsAtCompany: Number of years the employee has been with the company
    YearsInCurrentRole: Number of years the employee has been in the current role
    YearsSinceLastPromotion: Number of years since the last promotion
    YearsWithCurrManager: Number of years the employee has been with the current manager
    CommunicationSkill: Communication skill level
    Behaviour: Behaviour score of the employee
```
Data Preparation

    Exploratory Data Analysis (EDA): Conducted to understand the dataset, identify patterns, and detect anomalies.
    Data Cleaning: Handled missing values, outliers, and inconsistencies in the dataset.

Model Training

    Algorithms Used:
        Random Forest: A robust ensemble learning method for classification.
        4-Layer Neural Network: A deep learning model with multiple layers for improved prediction accuracy.
    Performance: Achieved an accuracy of 91% in predicting employee attrition probability.

Deployment

    Streamlit: Deployed the predictive model using Streamlit to create an interactive web application. Users can input employee attributes and receive attrition predictions.

Running the Application

To run the Streamlit application, click the below link:
https://employee-attrition-predictor-devarsh-kushagra.streamlit.app/
