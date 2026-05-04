# Stress Prediction using Machine Learning and Distributed Computing

Predicting stress levels using behavioural data with Machine Learning and Distributed Computing (Apache Spark).

## Project Overview

This project investigates whether mobile device usage, sleep behaviour, and lifestyle factors can predict self-reported stress levels. It compares a single-machine Machine Learning approach with a distributed Apache Spark MLlib implementation to evaluate both predictive accuracy and scalability.

The project was developed for CS5811 Distributed Data Analysis.

## Research Question

To what extent can mobile-device usage patterns, sleep behaviour, and lifestyle factors predict stress levels, and which machine-learning and high-performance computing approaches provide the most accurate and scalable predictions?

## Dataset

The dataset used is **Sleep, Screen Time and Stress Analysis**, containing:

- 15,000 records
- 13 original features
- Behavioural, lifestyle, sleep, and stress-related variables
- Target variable: `stress_level`

Dataset source:  
https://www.kaggle.com/datasets/jayjoshi37/sleep-screen-time-and-stress-analysis

## Repository Structure

```text
stress-prediction-ml-hpc_2562430/
│
├── Phase1_Data_Loading.ipynb
├── Phase2_EDA.ipynb
├── Phase3_Feature_Engineering.ipynb
├── Phase4_Train_Test_Split.ipynb
├── Phase5_ML_Prediction.ipynb
├── Phase6_HPC_Colab.ipynb
│
├── Output/
│   ├── processed data
│   ├── train/test splits
│   ├── model metrics
│   └── prediction outputs
│
├── figures/
│   ├── EDA figures
│   ├── PCA and clustering plots
│   ├── SHAP outputs
│   └── scalability plots
│
├── sleep_mobile_stress_dataset_15000.csv
└── README.md
