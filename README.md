# CREDIT-CARD-FRAUD-DETECTION-PAMS



## Introduction
Welcome to the [Project Name] repository! This project focuses on exploring and improving the performance of classification models using a pre-processed dataset. The dataset has already undergone Principal Component Analysis (PCA) transformation, eliminating the need for exploratory data analysis (EDA). Standard scaling has been applied, and two classification algorithms, Logistic Regression and K-Nearest Neighbors, have been employed on the imbalanced dataset.

## Overview
Briefly, this project aims to address classification challenges in a pre-processed dataset without the need for extensive data exploration. The focus is on applying standard scaling, handling class imbalance, and utilizing Logistic Regression and K-Nearest Neighbors for classification.

## Table of Contents
1. [Dataset](#dataset)
2. [Data Preprocessing](#data-preprocessing)
3. [Imbalance Handling](#imbalance-handling)
4. [Modeling](#modeling)
5. [Results](#results)
6. [Conclusion](#conclusion)

## Dataset
The dataset used in this project has already undergone Principal Component Analysis (PCA) transformation, reducing its dimensionality. No further Exploratory Data Analysis (EDA) is required, streamlining the analysis process.

## Data Preprocessing
Standard scaling has been applied to normalize the dataset, ensuring consistent feature scales for the classification models. This step is crucial for algorithms sensitive to varying feature magnitudes.

## Imbalance Handling
The dataset exhibits class imbalance, and to address this issue, both Logistic Regression and K-Nearest Neighbors have been applied directly to the imbalanced dataset.

## Modeling
Two widely used classification algorithms, Logistic Regression and K-Nearest Neighbors, were employed for the initial predictions. Following this, ROC AUC thresholds were utilized to enhance model performance.

## Results
The performance of the models was evaluated and compared. Subsequently, resampling techniques, specifically undersampling, were applied to mitigate class imbalance. The models were then re-evaluated using Logistic Regression and K-Nearest Neighbors.

## Conclusion
In summary, this project provides a comprehensive exploration of classification techniques on a pre-processed dataset. The utilization of standard scaling, direct application of models on imbalanced data, and subsequent model refinement through ROC AUC thresholds and resampling techniques are highlighted. The results and conclusions drawn from these analyses are detailed in the subsequent sections.

Feel free to explore the code and analysis in this repository. If you have any questions or suggestions, please don't hesitate to reach out!

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
