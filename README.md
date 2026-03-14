# Train-journey-prediction
This project focuses on predicting train journey duration using Machine Learning. The model analyzes train schedule data such as travel distance, number of stations, and other operational features to estimate the total journey time.
The project demonstrates the complete machine learning workflow, including data preprocessing, feature engineering, exploratory data analysis, model training, and evaluation using Python.

📌 Project Objectives

The main goals of this project are:
  - Analyze railway schedule data
  - Perform data preprocessing and feature engineering
  - Explore relationships between travel distance, stations, and journey time
  - Build a Linear Regression model to predict journey duration
  - Evaluate model performance using standard regression metrics

📂 Dataset

The dataset contains train schedule information with details such as:
  - Train number
  - Station codes
  - Arrival and departure times
  - Distance from the starting station
  - Route information
  - Train class availability (1A, 2A, 3A, SL)

Each record represents a station stop for a train route.

⚙️ Technologies Used

  - Python
  - Pandas
  - NumPy
  - Matplotlib
  - Scikit-learn
  - Jupyter Notebook

These tools were used for data analysis, visualization, and machine learning model development.

📊 Results

The analysis showed that:
  - Travel distance strongly influences journey duration.
  - Number of station stops increases travel time.
  - Average speed has an inverse relationship with journey duration.

The Linear Regression model successfully captured these relationships and provided reasonable predictions.
