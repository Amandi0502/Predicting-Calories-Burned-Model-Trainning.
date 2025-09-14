# Fitness Activity Calorie Prediction

## Project Overview
This project focuses on predicting calories burned based on physical activity data collected from fitness trackers. The dataset contains various activity metrics such as step counts, distances covered at different intensity levels, active minutes, and calories burned.

## Dataset Description
The dataset includes the following features:
- **Id**: Unique identifier for each user
- **ActivityDate**: Date when activity was recorded
- **TotalSteps**: Total number of steps taken
- **TotalDistance**: Total distance covered (miles)
- **TrackerDistance**: Distance recorded by the tracker
- **LoggedActivitiesDistance**: Distance from manually logged activities
- **VeryActiveDistance**: Distance during high-intensity activities
- **ModeratelyActiveDistance**: Distance during moderate-intensity activities
- **LightActiveDistance**: Distance during low-intensity activities
- **SedentaryActiveDistance**: Distance while sedentary
- **VeryActiveMinutes**: Minutes in very active physical activity
- **FairlyActiveMinutes**: Minutes in fairly active physical activity
- **LightlyActiveMinutes**: Minutes in lightly active physical activity
- **SedentaryMinutes**: Minutes in sedentary behavior
- **Calories**: Total calories burned (target variable)

## Project Tasks
The implementation addresses the following tasks:
1. Exploratory Data Analysis (EDA)
2. Feature and output identification
3. Missing value imputation
4. Outlier detection and removal
5. Feature selection and extraction
6. Data normalization
7. Building and optimizing at least two ML models
8. Model evaluation using appropriate techniques

## Implementation
The complete solution is implemented in a single Jupyter Notebook (`ML_SC_InClass_Exam_B9.ipynb`) that includes:
- Code implementation for all tasks
- Markdown explanations for methodological choices
- Visualizations and analysis results
- Model training and evaluation

## Requirements
- Python 3.7+
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

## How to Run
1. Clone the repository
2. Open the Jupyter Notebook
3. Run all cells sequentially
