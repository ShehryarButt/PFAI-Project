# Student Performance Analysis & CGPA Prediction

## Overview
This repository contains an end-to-end Data Science pipeline, covering everything from synthetic data generation to predictive modeling. The project analyzes student academic records (Class 9 to Class 12) to predict final CGPA categories, showcasing a complete workflow of data engineering, exploratory analysis, and machine learning.

## Project Structure
* **`Student_Data_Generation.ipynb`**: A script designed to generate synthetic student academic data using an Agent-Based Modeling (ABM) approach. It creates 400 student records with marks across four academic years and calculates a normalized CGPA for each entry.
* **`PfaiProject.ipynb`**: The core analytical notebook. It imports the generated dataset, performs statistical cleaning, exploratory data analysis (EDA), and implements Machine Learning models to categorize student performance.
* **`student_abm_data.csv`**: The primary dataset containing student marks and calculated CGPA metrics used for training and testing the models.

## Key Features
* **Synthetic Data Generation:** Uses an ABM-based methodology to simulate realistic student performance data.
* **Data Preprocessing:** Handles missing values, performs feature scaling, and cleans datasets for model readiness.
* **Exploratory Data Analysis (EDA):** Uses `matplotlib` and `seaborn` to visualize performance trends and statistical distributions.
* **Machine Learning Pipeline:** * Implements **Logistic Regression** and **Random Forest Classifier** to predict CGPA tiers ('Low', 'Medium', 'High').
    * Evaluates models using Accuracy, Precision, Recall, and Confusion Matrices.
* **Interactive Prediction:** Includes a built-in CLI tool that accepts user input to predict a student's CGPA category based on their marks.

## Tech Stack
* **Language:** Python 3
* **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
* **Environment:** Google Colab / Jupyter Notebook
