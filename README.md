# Predicting Event Interest - Logistic Regression Analysis

## Overview
This project uses logistic regression to predict whether a user will express 
interest in an event. 

## Repository Contents

| File | Description |
|------|-------------|
| `train.csv` | Original Kaggle file - core training data (user, event, interested) |
| `users.csv` | Original Kaggle file - user demographics |
| `events_matched.csv` | Derived from Kaggle events.csv - filtered to only events appearing in train.csv |
| `event_attendees_sample.csv` | Derived from Kaggle event_attendees.csv - sampled to 5,000 rows |
| `event_attendance_dataset.csv` | Final merged dataset used for modelling |
| `Predicting_Event_Interest_-_Making_the_Dataset.ipynb` | Notebook 1 - data preparation |
| `Predicting_Event_Interest_-_Logistic_Regression_Application.ipynb` | Notebook 2 - modelling and evaluation |

## How to Run
Run the notebooks in order:
1. `Predicting_Event_Interest_-_Making_the_Dataset.ipynb`
2. `Predicting_Event_Interest_-_Logistic_Regression_Application.ipynb`
