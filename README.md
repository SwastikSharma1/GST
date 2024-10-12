# GST

## Project Overview

This project implements a binary classification model using TensorFlow's Keras library. The model is designed to handle common challenges in machine learning, such as class imbalance, anomalies, and missing data. It preprocesses the data, builds and trains a neural network, and evaluates the model's performance.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Data Sources](#data-sources)
- [Installation](#installation)
- [Usage](#usage)
- [Model Structure](#model-structure)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Features

- Data preprocessing including merging datasets, one-hot encoding, and label encoding.
- Handling missing values and anomalies using Isolation Forest.
- Addressing class imbalance with SMOTE (Synthetic Minority Over-sampling Technique).
- Neural network training using Keras with cross-validation.
- Evaluation of model accuracy on unseen test data.

## Requirements

To run this project, you need the following Python libraries:

- pandas
- numpy
- scikit-learn
- imbalanced-learn
- tensorflow

You can install the required libraries using pip:

```bash
pip install pandas numpy scikit-learn imbalanced-learn tensorflow
