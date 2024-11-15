
# Rainfall Prediction Using Machine Learning

This project aims to predict rainfall using machine learning techniques. The workflow includes data preprocessing, exploratory data analysis (EDA), feature engineering, and training various predictive models.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Project Workflow](#project-workflow)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Overview
Rainfall prediction is crucial for agriculture, water resource management, and disaster preparedness. This project leverages machine learning to predict rainfall based on historical weather data.

## Dataset
The dataset contains historical weather features such as:
- Temperature
- Humidity
- Pressure
- Wind Speed
- Rainfall

Ensure the dataset is formatted as required and placed in the `data/` directory.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/DolphinRidz/Rainfall-Prediction.git
   cd rainfall-prediction
   ```
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

## Project Workflow
The project is divided into the following steps:
1. **Data Preprocessing**:
   - Handle missing values
   - Feature scaling and encoding
2. **Exploratory Data Analysis (EDA)**:
   - Visualize trends and correlations
3. **Feature Engineering**:
   - Select relevant features
   - Create new derived features
4. **Model Training**:
   - Train and evaluate machine learning models like:
     - Linear Regression
     - Decision Trees
     - Random Forest
     - Gradient Boosting
5. **Model Evaluation**:
   - Use Random Forest

## Usage
1. Run the Jupyter Notebook to execute the code step-by-step:
   ```bash
   jupyter notebook Rainfall_Prediction_Machine_Learning.ipynb
   ```
2. Ensure that the dataset is in the correct directory before running the notebook.

## Results
The model's performance and insights from EDA are documented in the notebook. Key findings include:
- [Insert key results, e.g., RMSE of the best model]

## License
This project is licensed under the MIT License.
