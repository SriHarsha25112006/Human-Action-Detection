# Human Action Detection

This project implements a machine learning system for detecting human actions based on multimodal body sensor data. It utilizes the MHEALTH (Mobile HEALTH) dataset to classify various physical activities.

## Features

- **Activity Recognition**: Classifies 12 different physical activities (standing, sitting, walking, running, cycling, etc.).
- **Multimodal Sensing**: Processes data from chest, wrist, and ankle sensors (accelerometers, gyroscopes, magnetometers).
- **ML Analysis**: Includes data preprocessing, feature engineering, and model training in a Jupyter Notebook environment.

## Dataset

The project uses the **MHEALTH Dataset**, which is designed for human behavior analysis based on multimodal body sensing.

- **Kaggle Link**: [Mobile Health Human Behavior Analysis](https://www.kaggle.com/datasets/gaurav2022/mobile-health)
- **Note**: Large data files are excluded from this repository. Please download the dataset from Kaggle and place the files in the project root to run the notebook.

## Installation & Setup

1. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/Scripts/activate  # On Windows: venv\Scripts\activate
   ```

2. **Install Requirements**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download Dataset**:
   - Download from the [Kaggle link](https://www.kaggle.com/datasets/gaurav2022/mobile-health).
   - Extract and place the data files (e.g., `mhealth_raw_data.csv`) in the project directory.

4. **Run the Notebook**:
   - Open and run `Human_Action_Detector.ipynb`.
