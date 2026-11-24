# data-preparation-baseline
First machine learning baseline project using the Iris dataset
# Data Preparation and Baseline Model

## Overview
This project prepares the Iris dataset and builds a simple machine learning baseline for flower species classification.

## Dataset
The Iris dataset is used. It contains four numerical features representing flower measurements and three species classes.

## Methodology
1. Loaded the Iris dataset.
2. Split the data into training (80%) and testing (20%) sets.
3. Used stratified splitting to preserve class proportions.
4. Built a majority-class baseline using DummyClassifier.
5. Evaluated the baseline using accuracy on the test set.

## Model
DummyClassifier with the `most_frequent` strategy.

## Evaluation
The model was evaluated using test-set accuracy.

**Baseline Accuracy:** Replace this with the accuracy you obtained.

## How to Run
1. Open the notebook using Google Colab or Jupyter Notebook.
2. Run all cells in order.

## Tools Used
- Python
- Pandas
- Scikit-learn
- Google Colab
