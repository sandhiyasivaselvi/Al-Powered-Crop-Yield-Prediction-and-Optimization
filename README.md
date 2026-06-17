# Al-Powered-Crop-Yield-Prediction-and-Optimization

## Problem Statement

Agriculture is highly dependent on environmental factors such as weather, soil quality, and irrigation. Farmers often face difficulties in estimating crop yield accurately, which can lead to poor resource management and reduced productivity. Traditional prediction methods are less efficient and may not provide reliable results. Therefore, an AI-powered system is required to predict crop yield and provide optimization recommendations to support better farming decisions.

## Objectives

* Predict crop yield using Machine Learning algorithms.
* Analyze agricultural data such as soil, weather, and crop information.
* Provide recommendations for fertilizer and irrigation management.
* Help farmers improve productivity and resource utilization.
* Support data-driven decision-making in agriculture.

## Requirement Gathering

### Functional Requirements

* Farmers should be able to enter crop, soil, and weather details.
* The system should collect historical agricultural data.
* The AI/ML model should predict crop yield based on input data.
* The system should provide recommendations for fertilizers and irrigation.
* Users should be able to view prediction results and optimization suggestions.
* Admin should be able to manage datasets and monitor system performance.

### Non-Functional Requirements

* The system should provide accurate crop yield predictions.
* The application should be user-friendly and easy to use.
* Prediction results should be generated quickly.
* The system should securely store user and agricultural data.
* The application should be scalable for multiple users and regions.


### Data Requirements

* Historical crop yield data
* Weather data (temperature, rainfall, humidity)
* Soil data (pH, nutrients, moisture)
* Fertilizer and irrigation information

### Stakeholders

* Farmers
* Agricultural Experts
* Researchers
* System Administrator

## Technologies Used

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* Python
* Flask

### Database

* MySQL

### Machine Learning Libraries

* Pandas
* NumPy
* Scikit-learn
* Matplotlib

## Dataset Information

The dataset contains agricultural information including:

* Crop Type
* Soil Type
* Soil pH
* Temperature
* Rainfall
* Humidity
* Fertilizer Usage
* Irrigation Level
* Previous Yield
* Area Cultivated

### Target Variable

* Crop Yield (tons/hectare)

## System Modules

### 1. User Registration Module

Allows farmers to create and manage accounts.

### 2. Login & Authentication Module

Provides secure access to the system.

### 3. Farm Data Management Module

Stores crop, soil, and farming details.

### 4. Weather & Soil Analysis Module

Analyzes environmental conditions affecting crop growth.

### 5. Crop Yield Prediction Module

Uses Machine Learning algorithms to predict crop yield.

### 6. Crop Optimization Module

Provides recommendations for fertilizer, irrigation, and crop selection.

### 7. Admin Management Module

Manages users, datasets, and system settings.

### 8. Reporting & Dashboard Module

Displays prediction results and farming insights.

## Machine Learning Workflow

1. Data Collection
2. Data Preprocessing
3. Feature Selection
4. Model Training
5. Crop Yield Prediction
6. Performance Evaluation
7. Performance Evaluation
8. Recommendation Generation

## Dataset Attributes

| Attribute Name   | Description                                     |
| ---------------- | ----------------------------------------------- |
| Farm_ID          | Unique identifier for each farm                 |
| Crop_Type        | Type of crop (Rice, Wheat, Maize, Cotton, etc.) |
| Soil_Type        | Type of soil (Clay, Loamy, Sandy, etc.)         |
| Soil_pH          | pH value of the soil                            |
| Temperature      | Average temperature (°C)                        |
| Rainfall         | Annual rainfall (mm)                            |
| Humidity         | Humidity percentage                             |
| Fertilizer_Usage | Amount of fertilizer used (kg/hectare)          |
| Irrigation_Level | Water supplied to the crop                      |
| Area_Cultivated  | Cultivated land area (hectares)                 |
| Previous_Yield   | Previous year's crop yield                      |
| Crop_Yield       | Final crop yield (Target Variable)              |

These attributes were selected because soil characteristics, weather conditions, fertilizer usage, and irrigation levels directly affect crop growth and productivity. The **Crop_Yield** attribute is used as the target variable that the Machine Learning model learns to predict, helping farmers improve agricultural planning and decision-making.


