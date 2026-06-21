# ⚡ Electric Vehicle Range Prediction

## Overview

This project is a Machine Learning application that predicts the **driving range of Electric Vehicles (EVs)** using vehicle specifications such as battery capacity, top speed, efficiency, torque, drivetrain, and other technical attributes. The model is trained on a dataset containing specifications of hundreds of EV models and is deployed through an interactive web application.

## Project Objective

The goal of this project is to leverage machine learning techniques to estimate an EV's driving range based on its technical specifications, helping users compare vehicles and understand the factors that influence EV performance.

## Features

* 🚗 Predict EV driving range using vehicle specifications
* 📊 Data preprocessing and feature engineering
* 🤖 Machine Learning model built with Gradient Boosting
* 🎯 Accurate range estimation based on key EV attributes
* 🌐 Interactive web interface built with Streamlit
* 📈 Real-world EV dataset with 400+ vehicle records

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Streamlit
* Gradient Boosting Regressor

## Dataset Information

The dataset includes EV specifications such as:

* Brand & Model
* Battery Capacity (kWh)
* Top Speed (km/h)
* Torque (Nm)
* Efficiency (Wh/km)
* Acceleration (0–100 km/h)
* Fast Charging Power
* Drivetrain
* Vehicle Segment
* Dimensions and Seating Capacity

## Machine Learning Workflow

1. Data Collection & Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Training
5. Model Evaluation
6. Model Deployment with Streamlit

## Project Structure

```text
├── app.py
├── gradient_boosting_model.pkl
├── electric_vehicles_spec_2025.csv
├── requirements.txt
└── README.md
```

## Use Cases

* EV comparison and analysis
* Automotive data science projects
* Machine learning regression applications
* EV market research and insights

## Results

The Gradient Boosting model learns complex relationships between EV specifications and driving range, enabling reliable predictions that can support consumers, researchers, and automotive enthusiasts in evaluating electric vehicles.

⭐ If you found this project useful, consider giving it a star and contributing to future improvements! 🚀
