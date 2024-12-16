# Gym Insights: Analyzing Exercise Patterns and Performance Across Experience Levels
Team members:
- Angelina Zhumadilova
## Project Motivation and Goals
Fitness is a personal journey, yet gyms often face challenges in
tailoring resources and plans to diverse member needs. By
analyzing gym data, this project identifies patterns and trends in
workouts, helping trainers and fitness apps provide personalized
recommendations. The ultimate goal is to optimize the fitness
experience for all levels, improving satisfaction, performance, and
resource allocation through actionable insights.
I analyzed a dataset containing information about gym-goers'
demographics, workout types, and performance metrics.
## Project Goals
- Data Cleaning: Standardize and preprocess the dataset for analysis.
- Data Visualization: Create compelling visualizations to explore trends, identify workout patterns, and highlight key differences across experience levels.
- Classification Model: Develop a machine learning model to predict a gym member's experience level.
- Regression Model: Build a predictive model to estimate calories burned during workouts.
- Recommendations & Insights: Analyze the findings to provide actionable recommendations for optimizing gym operations, tailoring fitness plans, and improving fitness app personalization.
## Repository Contents
### 1. Dataset
- File: gym_members_exercise_tracking.csv
- Source: https://www.kaggle.com/datasets/valakhorasani/gym-members-exercise-dataset/data
- Description: dataset provides a detailed overview of gym members' exercise routines, physical attributes, and fitness metrics. It contains 973 samples of gym data, including key performance indicators such as heart rate, calories burned, and workout duration.
- gym_members_exercise_cleaned.csv - data after cleaning to train model
#### Data Format:
- Age: Age of the gym member.
- Gender: Gender of the gym member (Male or Female).
- Weight (kg): Member’s weight in kilograms.
- Height (m): Member’s height in meters.
- Max_BPM: Maximum heart rate (beats per minute) during workout sessions.
- Avg_BPM: Average heart rate during workout sessions.
- Resting_BPM: Heart rate at rest before workout.
- Session_Duration (hours): Duration of each workout session in hours.
- Calories_Burned: Total calories burned during each session.
- Workout_Type: Type of workout performed (e.g., Cardio, Strength, Yoga, HIIT).
- Fat_Percentage: Body fat percentage of the member.
- Water_Intake (liters): Daily water intake during workouts.
- Workout_Frequency (days/week): Number of workout sessions per week.
- Experience_Level: Level of experience, from beginner (1) to expert (3).
- BMI: Body Mass Index, calculated from height and weight.
### 2. Notebooks
data_cleaning_and_vizualization.ipynb - Data Cleaning and Vizualization
models.ipynb - model building
### 4. Documentation
README.md (This file): Overview of the project, structure, and usage.
G9_report.pdf - homework 10

## Getting Started
### 1. Prerequisites
Python 3.8+
Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, plotly, etc.
### 2. Running the Analysis
1. Clone the repository:
```
git clone https://github.com/angelinazhuma/Gym-insights.git
cd Gym-insights
```
 2. Run the notebook:
```
jupyter notebook
```
- Data Cleaning and Vizualization - run data_cleaning_and_vizualization.ipynb to clean and preprocess the dataset and expolre vizualization
- Use models.ipynb to train the model
- View the insights in G9_report.pdf
  
