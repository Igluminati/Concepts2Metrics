# Concepts2Metrics

## TLDR Description

Internship Project: Concepts2Metrics - Collaborative Data-Driven Insights  During my internship, I collaborated with Kristupas Jucaitis on 'Concepts2Metrics,' where we extracted data-driven insights from product concepts.

**Leveraging Tagged Product Concepts for Data-Driven Insights**

## Table of Contents
1. [Introduction](#introduction)
2. [Data](#data)
   - [Data Source](#data-source)
   - [Data Preprocessing](#data-preprocessing)
3. [Analysis](#analysis)
   - [Exploratory Data Analysis](#exploratory-data-analysis)
   - [Findings](#findings)
   - [Feature Engineering](#feature-engineering)
4. [Modeling](#modeling)
   - [Model Creation](#model-creation)
   - [Model Results](#model-results)
5. [Reflections](#reflections)
6. [Future Improvements](#future-improvements)

## Introduction

Concepts2Metrics is a project aimed at leveraging tagged product concepts for data-driven insights. This README provides an overview of the project's key components and findings.

## Data

### Data Source

The project uses a dataset with limited data volume, containing only 717 rows. Small datasets can present challenges such as over-fitting and limited generalizability.

### Data Preprocessing

The dataset has sparsity and dominant binary columns. These characteristics require careful preprocessing and feature engineering.

## Analysis

### Exploratory Data Analysis

The project includes exploratory data analysis to understand correlations between different data metrics. Notably, 'Distinctiveness' exhibits a negative relationship with other metrics.

### Findings

The findings indicate the need to treat 'Distinctiveness' differently from other metrics.

### Feature Engineering

Feature engineering involves dimensionality reduction using Principal Component Analysis (PCA). The project aims to filter out noise and irrelevant features, potentially leading to more accurate clusters.

## Modeling

### Model Creation

The project employs the XGBoost algorithm for regression tasks. XGBoost is known for its accuracy and robustness. It sequentially trains trees, with each tree focusing on the mistakes of the previous ones.

### Model Results

The project evaluates model performance using metrics like Root Mean Squared Error and R-squared. The low RMSE scores indicate accurate predictive performance, but R-squared suggests potential overfitting.

## Reflections

### Struggles

- Challenges in mastering XGBoost and machine learning
- Dealing with a small dataset prone to overfitting
- Too much focus on unnecessary details
- Inclusion of duplicate tags in features

### Successes

- Effective task distribution
- Clear and efficient communication within the team
- Learning and improvement throughout the project

## Future Improvements

- Continue refining the feature engineering process
- Consider data augmentation techniques to expand the dataset and improve results

