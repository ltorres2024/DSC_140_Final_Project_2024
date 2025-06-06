# Soccer Analysis and Machine Learning – DSC 140

As a soccer fan, this project dives into the analytics behind goal-scoring in Europe’s top 5 leagues using event data from professional matches. The dataset comes from the **Football Events** dataset on Kaggle:

[Football Events Dataset on Kaggle](https://www.kaggle.com/datasets/secareanualin/football-events)

## Overview

The project focuses on:
- Cleaning and merging event data with match metadata
- Analyzing shot outcomes and goal distributions by country and shot placement
- Visualizing trends using bar charts and pie charts
- Running statistical tests (Chi-square, Kolmogorov-Smirnov) on shot patterns

## Machine Learning Models

### K-Nearest Neighbors (KNN)
- Explores accuracy across varying values of *k*
- Evaluates prediction performance on shot placement vs. goal outcome
- Uses a confusion matrix for error analysis

### Neural Network (TensorFlow/Keras)
- Two hidden layers using ReLU and sigmoid activations
- Predicts goal probability from shot placement data
- Trained and tested on OSC’s high-performance cluster due to dataset size

## Visualizations

- **Shot Outcome Distribution (Pie Chart)**
- **Goals vs. No-Goals per Country (Bar Plot)**
- **Goal Probability by Shot Placement**
- **Model Accuracy vs. K (KNN)**
- **Confusion Matrix for KNN Predictions**

##  Tools Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn` (KNN, accuracy, confusion matrix)
- `tensorflow.keras` (Neural Network)
- `scipy.stats` (Chi-square, KS test)

>  **Note:** Paths to the dataset will need to be updated based on your local system.
