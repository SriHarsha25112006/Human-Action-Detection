# Human Action Detection

This project implements a machine learning system for detecting human actions based on multimodal body sensor data. It utilizes the MHEALTH (Mobile HEALTH) dataset to classify various physical activities.

## Features

- **Activity Recognition**: Classifies 12 different physical activities (standing, sitting, walking, running, cycling, etc.).
- **Multimodal Sensing**: Processes data from chest, wrist, and ankle sensors (accelerometers, gyroscopes, magnetometers).
- **ML Analysis**: Includes data preprocessing, feature engineering, and model training in a Jupyter Notebook environment.

## Dataset

The project uses the **MHEALTH Dataset**, which is designed for human behavior analysis based on multimodal body sensing.

- **Kaggle Link**: [Mobile Health Human Behavior Analysis](https://www.kaggle.com/datasets/gaurav2022/mobile-health-human-behavior-analysis)
- **Note**: The raw data file (`mhealth_raw_data.csv`) is excluded from this repository due to size. Please download it from Kaggle and place it in the project root to run the notebook.

## Setup

1. Install requirements: `pip install pandas numpy matplotlib seaborn catboost scikit-learn`.
2. Open and run `Human_Action_Detector.ipynb`.
