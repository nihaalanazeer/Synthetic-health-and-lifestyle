# Synthetic-health-and-lifestyle
ynthetic Health and Lifestyle Dataset including demographics, daily habits, exercise, diet, and vital signs, created for data analysis, machine learning, and predictive modeling in health and wellness applications.
# Synthetic Health and Lifestyle Dataset

![License](https://img.shields.io/badge/License-MIT-green) ![Python](https://img.shields.io/badge/Python-3.8-blue)

## Description
This **Synthetic Health and Lifestyle Dataset** contains simulated data about individuals' demographics, daily habits, exercise, diet, and vital signs. It is designed for **data analysis, exploratory studies, and machine learning** applications in health and wellness prediction.

## Dataset Features
The dataset typically includes the following columns:

| Column Name           | Description                                                      |
|----------------------|------------------------------------------------------------------|
| `Person_ID`           | Unique identifier for each individual                             |
| `Age`                 | Age of the individual in years                                    |
| `Gender`              | Gender of the individual (Male/Female/Other)                     |
| `Height_cm`           | Height in centimeters                                             |
| `Weight_kg`           | Weight in kilograms                                               |
| `BMI`                 | Body Mass Index calculated from height and weight                |
| `Daily_Steps`         | Average daily step count                                          |
| `Sleep_Hours`         | Average hours of sleep per day                                     |
| `Diet_Type`           | Dietary preference (Vegetarian/Non-Vegetarian/Vegan/etc.)        |
| `Water_Intake_Liters` | Average daily water intake in liters                               |
| `Exercise_Minutes`    | Average daily exercise duration in minutes                        |
| `Smoking_Status`      | Smoker/Non-Smoker                                                 |
| `Alcohol_Consumption` | Average number of alcoholic drinks per week                       |
| `Heart_Rate`          | Resting heart rate in beats per minute                             |
| `Blood_Pressure_Sys`  | Systolic blood pressure                                           |
| `Blood_Pressure_Dia`  | Diastolic blood pressure                                          |
| `Cholesterol_mg/dL`   | Total cholesterol level                                           |
| `Health_Score`        | Synthetic overall health score (0–100)                            |

## Dataset Size
- **Number of records:** ~10,000 (can vary depending on generation parameters)  
- **Number of features:** 17 (excluding `Person_ID`)  

## Usage
This dataset can be used for:
- Predictive modeling for health outcomes  
- Exploratory Data Analysis (EDA) and visualization  
- Feature engineering and synthetic data experiments  
- Machine learning practice on health-related datasets  

### Example Code
```python
import pandas as pd

# Load dataset
data = pd.read_csv("synthetic_health_lifestyle.csv")

# Display first 5 rows
print(data.head())

