# Accident Prediction Model — AI/ML

A machine learning-based system designed to predict accident risk using traffic and environmental conditions such as vehicle speed, weather, road condition, lane deviation, and vehicle load.

## Features

- Accident risk prediction using machine learning
- Traffic and environmental condition analysis
- Multiple input features for prediction
- Data preprocessing and feature handling
- Model training and evaluation
- Interactive prediction interface using Streamlit

## Input Features

The model uses the following parameters:

- **Speed:** Vehicle speed in km/h
- **Weather:** Clear, Rain, or Fog
- **Road Condition:** Good or Slippery
- **Lane Deviation:** Indicates whether the vehicle deviates from its lane
- **Vehicle Load:** Light, Medium, or Heavy

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Random Forest
- Logistic Regression
- Streamlit
- Matplotlib / Seaborn

## Machine Learning Workflow

1. Collect and prepare the dataset
2. Perform data preprocessing
3. Select relevant features
4. Split the dataset into training and testing sets
5. Train machine learning models
6. Evaluate model performance
7. Use the trained model for accident-risk prediction
8. Deploy the prediction interface using Streamlit

## Models

The project explores machine learning classification models including:

- Random Forest Classifier
- Logistic Regression

The Random Forest model can be configured with class balancing to handle imbalanced accident-risk classes.

## Application

The Streamlit interface allows users to enter vehicle and environmental conditions and receive an accident-risk prediction.

## Project Structure

```text
Accident-Prediction-Model-AI-ML/
│
├── app.py
├── model.py
├── dataset.csv
├── requirements.txt
├── README.md
└── notebooks/
    └── model_training.ipynb
```

## Potential Applications

- Intelligent transportation systems
- Road safety analysis
- Driver assistance systems
- Traffic monitoring
- Predictive transportation analytics

## Future Improvements

- Use real-world traffic datasets
- Integrate GPS and real-time vehicle data
- Add additional road and traffic features
- Improve class imbalance handling
- Compare additional machine learning models
- Deploy the model as a cloud-based API
- Integrate with IoT vehicle sensors

## Author

Guda Rishindra
