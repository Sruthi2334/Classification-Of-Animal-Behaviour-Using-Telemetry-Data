# Animal Behaviour Classification using Telemetry Data

A machine learning project for classifying animal behaviour using accelerometer-based telemetry data.

## Overview

This work compares two approaches:

* XGBoost (feature-based model)
* CNN-LSTM (deep learning model for time-series data)

The objective is to evaluate how well a unified pipeline performs across different species.

## Dataset

BEBE (Bio-logger Ethogram Benchmark) dataset:

* Dog dataset (12 sensor channels, 12 behaviours)
* Polar bear dataset (3 sensor channels, 10 behaviours) 

## Results

* CNN-LSTM outperforms XGBoost on dog dataset (better accuracy and macro-F1)
* Both models achieve high accuracy (~95%) on polar bear dataset
* Low macro-F1 highlights class imbalance (accuracy–F1 paradox)

## Key Insight

Accuracy alone is not reliable for imbalanced datasets; macro-F1 is a better evaluation metric for behaviour classification.

## Author

Sruthi B
