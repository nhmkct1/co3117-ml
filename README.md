# CO3117 Machine Learning — Individual Longitudinal Assignment

## Project Overview

This repository contains my individual longitudinal learning portfolio for CO3117 Machine Learning.

The project follows the principle:

**One Dataset, One Use Case, Many Models.**

The same dataset, prediction target, split policy, evaluation protocol, and test population will be kept fixed throughout the semester.

---

## Dataset

**Dataset:** UCI Human Activity Recognition Using Smartphones

**Use case:** Predict a person's current physical activity from smartphone inertial measurements.

**Target:** 6 activity classes.

---

## Experimental Protocol

### Primary Metric
Macro-F1

### Secondary Metrics
- Accuracy
- Confusion Matrix

### Random Seed
42

### Data Split Policy
The dataset split protocol will remain fixed throughout the project.

Validation will be performed only within the training population.

The final test set will remain sealed and will not be used for hyperparameter tuning.

### Preprocessing Policy
All preprocessing operations, including scaling, feature selection, PCA, or other learned transformations, will be fitted using training data only.

---

## Repository Structure

- `docs/`: theory notes and weekly learning posts
- `exercises/`: handwritten written-exam drills
- `exam/`: exam preparation artifacts
- `src/`: reusable implementation code
- `experiments/`: controlled experiments
- `tests/`: unit and sanity tests
- `results/`: metrics and figures
- `report/`: formal submission reports

---

## Models

Planned model families include:

- Decision Tree
- Perceptron
- Neural Networks / Backpropagation
- Naive Bayes
- Genetic Algorithm
- Bayesian Networks
- Hidden Markov Models
- SVM
- PCA / LDA
- Bagging / Boosting
- Logistic / Softmax Regression
- CRF suitability analysis