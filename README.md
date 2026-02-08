#  Daily Gym Attendance & Workout Prediction using Machine Learning

# Project Overview
This project uses Machine Learning techniques to analyze daily gym activity data and predict whether a person will attend the gym. It also helps in understanding workout behavior patterns based on lifestyle and activity-related factors.


# Objectives
- Analyze gym attendance patterns
- Perform Exploratory Data Analysis (EDA)
- Build a machine learning classification model
- Evaluate model performance
- Extract meaningful insights from data


# Machine Learning Approach
- **Problem Type:** Classification
- **Algorithm Used:** Random Forest Classifier
- **Target Variable:** Attendance (Yes / No)


# Dataset Description
The dataset includes the following features:

| Feature | Description |
|-------|------------|
| Day | Day of the week |
| Time | Workout time (Morning / Evening) |
| EnergyLevel | Energy level of the user |
| SleepHours | Number of sleep hours |
| PreviousDayWorkout | Workout done on previous day |
| Attendance | Gym attendance (Target variable) |
| WorkoutType | Type of workout activity |


# Exploratory Data Analysis (EDA)
EDA was performed to:
- Check missing values
- Analyze target variable distribution
- Understand feature relationships
- Identify patterns and trends

Visualizations used:
- Attendance distribution plot
- Feature vs Attendance plots
- Correlation heatmap


# Project Structure

gym-attendance-ml/
│── gym_data.csv
│── eda.ipynb
│── model_training.ipynb
│── requirements.txt
│── README.md
