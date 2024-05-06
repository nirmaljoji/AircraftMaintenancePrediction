# Predictive Maintenance for NASA Turbofan Jet Engines

## Overview
This project aims to implement predictive maintenance techniques for NASA Turbofan jet engines using time series sensor data. The dataset comprises sensor readings from multiple engine cycles, with each cycle containing data from 25 sensors. Notably, the last cycle in the training dataset marks the point at which engine failure occurred. The objective is to develop models that can predict engine failure before it happens, enabling proactive maintenance and minimizing downtime.

## Project Structure
1. **Data Exploration:** Explore the dataset to understand its structure, patterns, and characteristics. This phase involves statistical analysis, visualization, and feature engineering to uncover insights indicative of impending engine failure.
2. **Exploring KNN and Regressors:** Investigate the performance of various machine learning algorithms such as KNN (K-Nearest Neighbors) and regressors (e.g., Random Forest, Gradient Boosting) for predictive modeling. This step includes data preprocessing, model training, and evaluation.
3. **Using LSTM:** Implement LSTM (Long Short-Term Memory) recurrent neural networks, a specialized architecture for sequence prediction tasks, to develop predictive models for engine failure. LSTM models will be trained on the time series sensor data and evaluated for their ability to forecast the remaining useful life of jet engines.

## How to Run
1. Clone the repository to your local machine.
2. Navigate to the `notebooks` directory.
3. Execute the Jupyter notebooks in the following order:
   - `1_Data_Exploration.ipynb`
   - `2_Exploring_KNN_and_Regressors.ipynb`
   - `3_Using_LSTM.ipynb`
4. Follow the instructions within each notebook to explore data, preprocess features, train models, and evaluate predictions.

## Results
- Identification of key features and patterns indicative of engine failure through data exploration.
- Performance evaluation of KNN, regressors, and LSTM models in predicting the remaining useful life of jet engines.

## Conclusion
This project demonstrates the application of predictive maintenance techniques to NASA Turbofan jet engines using time series sensor data. By exploring various machine learning algorithms and LSTM models, it is possible to predict engine failures in advance, allowing for proactive maintenance and minimizing downtime. Such approaches have significant implications for improving the reliability, safety, and cost-effectiveness of jet engine operations.
