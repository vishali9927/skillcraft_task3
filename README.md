# Bank Marketing Decision Tree Classifier

This repository contains a Python implementation of a Decision Tree Classifier applied to the Bank Marketing dataset. The goal is to predict whether a client will subscribe to a term deposit (`yes` or `no`) based on various attributes.

---

## Dataset

The dataset used in this project is the Bank Marketing dataset, which is publicly available from the UCI Machine Learning Repository or other sources. The CSV file used here (`bank_sample.csv`) is assumed to have a semicolon (`;`) delimiter.

---

## Project Structure

- `bank_sample.csv` - Dataset file (not included in this repo, add separately)
- `bank_marketing_decision_tree.py` - Python script containing the full pipeline for:
  - Data loading and preprocessing
  - One-hot encoding of categorical variables
  - Train/test split
  - Training a Decision Tree Classifier
  - Model evaluation (accuracy, classification report, confusion matrix)
  - Visualization of the decision tree

---

## Requirements

- Python 3.x
- pandas
- scikit-learn
- matplotlib
