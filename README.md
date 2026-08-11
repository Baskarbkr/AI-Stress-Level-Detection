# AI-Based Stress Level Detection Using Multimodal Physiological Data

## Overview

This project presents an AI-based system for detecting stress levels using multimodal physiological data. The system analyzes physiological signals such as ECG, GSR, and temperature and applies machine learning techniques to identify stress conditions.

The project uses the WESAD (Wearable Stress and Affect Detection) dataset for model development and evaluation.

## Objectives

- Detect stress using physiological signals.
- Process and extract meaningful features from ECG, GSR, and temperature signals.
- Train and evaluate machine learning models.
- Integrate the prediction system with Firebase.
- Provide a foundation for real-time stress monitoring using ESP32.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Machine learning and data processing |
| Google Colab | Development environment |
| NumPy | Numerical processing |
| Pandas | Data processing |
| Scikit-learn | Machine learning |
| Matplotlib | Data visualization |
| Firebase Realtime Database | Real-time data storage |
| Flask | REST API |
| ESP32 | IoT hardware |

## Dataset

### WESAD Dataset

The project uses the WESAD (Wearable Stress and Affect Detection) dataset containing multimodal physiological signals.

The complete dataset is **not included in this repository**.

## Machine Learning

The project explores multiple machine learning algorithms, including:

- Logistic Regression
- Naive Bayes
- Decision Tree
- Random Forest
- Extra Trees
- XGBoost

The final model selection is based on the performance obtained during experimentation.

## System Architecture

![System Architecture](images/system_architecture.png)

## Physiological Signal Analysis

![Physiological Signals](images/physiological_signals.png)

## Firebase Integration

![Firebase Database](images/firebase_database.png)

## Stress Prediction

![Stress Prediction](images/stress_prediction.png)

## Project Structure

```text
