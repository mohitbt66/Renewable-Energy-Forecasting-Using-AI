# Renewable-Energy-Forecasting-using-Artificial-Intelligence

Solar energy is one of the most promising and widely adopted renewable energy sources today. However, solar power generation is highly dependent on weather conditions, which are often variable and unpredictable. This makes accurate forecasting of solar energy generation a critical challenge. In this project, Artificial Intelligence (AI) techniques are applied to forecast solar power generation, aiming to improve system efficiency, grid stability, and energy reliability.

A publicly available solar power generation dataset from Kaggle is used for this project. After thorough data cleaning and error checking, Exploratory Data Analysis (EDA) was performed to identify the most influential features in predicting solar power output. Feature engineering was then conducted to create additional attributes—such as solar irradiance trends, ambient temperature patterns, and time-based variables—to help the models learn more effectively.

To prepare the data for modeling, normalization and standardization techniques were applied. Time-series reshaping was carried out for sequence-based models such as LSTM and BiLSTM. The dataset was subsequently divided into training and testing sets to evaluate model performance under realistic conditions.

A variety of machine learning and deep learning models were trained and compared, including:

Long Short-Term Memory (LSTM)

Bidirectional LSTM

Adaptive Neuro-Fuzzy Inference System (ANFIS)

XGBoost (Extreme Gradient Boosting)

SVM-ANN (Support Vector Machine combined with Artificial Neural Network)

Support Vector Regression (SVR)

These models were evaluated using standard performance metrics:

Root Mean Squared Error (RMSE)

Mean Absolute Error (MAE)

Coefficient of Determination (R² Score)

This project highlights the potential of AI-based models to provide accurate solar energy forecasts, thereby supporting energy providers, grid operators, and policymakers in planning, load balancing, and optimizing storage.

Steps to Run the Project:

1. Clone the GitHub repository:

git clone https://github.com/mohitbt66/Renewable-Energy-Forecasting-using-Artificial-Intelligence

2. Download and unzip the dataset:

Dataset URL: https://www.kaggle.com/datasets/anikannal/solar-power-generation-data

3. Run the code:

Launch Jupyter Notebook and run the notebooks provided in the repository.
