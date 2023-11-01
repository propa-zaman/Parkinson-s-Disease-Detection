# Parkinson's Disease Detection using SVM (Support Vector Machines)

## Table of Contents
- [Introduction](#introduction)
- [Dependencies](#dependencies)
- [Data Collection and Analysis](#data-collection-and-analysis)
- [Data Pre-Processing](#data-pre-processing)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Building a Predictive System](#building-a-predictive-system)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This is a Machine Learning project that aims to detect Parkinson's Disease in individuals using various vocal feature data. The model is trained using the Support Vector Machines algorithm.

## Dependencies

- Python 3.x
- pandas
- numpy
- scikit-learn

## Data Collection and Analysis

The dataset used in this project is a CSV file containing various vocal features. 
- Number of Columns: `24`
- Number of Rows: `195`
- No missing values were found.
- Target Variable: `status`
  - 1 --> Parkinson's Positive
  - 0 --> Healthy

## Data Pre-Processing

Steps involved in pre-processing:
- Separated features and target variables
- Data Standardization

## Model Training

The model was trained using a linear kernel Support Vector Machines (SVM) algorithm.

## Model Evaluation

The model's performance was evaluated based on its accuracy on both the training and test data.

- Training Data Accuracy: `87%`
- Test Data Accuracy: `92%`

## Building a Predictive System

The final part of the code includes a predictive system that takes vocal feature data and outputs whether the individual is likely to have Parkinson's Disease or not.

## Usage

To use this project:
1. Clone the repository.
2. Install dependencies.
3. Run `your_script_name.py`.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.
