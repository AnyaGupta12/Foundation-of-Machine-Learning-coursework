# Foundation-of-Machine-Learning-coursework
This repository contains my solutions and code submissions for the Foundations of Machine Learning course. It includes assignments focused on core ML concepts such as supervised and unsupervised learning, model evaluation, optimization techniques, and algorithm implementation using Python.

# Assignment 1 – Decision Trees

This assignment focuses on implementing and evaluating decision tree classifiers from scratch using the Wine Quality dataset.

## Objective

To classify wines as high-quality (label 1) or not (label 0) based on their chemical properties. The dataset has been preprocessed into a binary classification task using 11 features (excluding the target label).

## Tasks

### 1. Decision Tree Implementation 
Implemented a custom decision tree classifier using:
- Binary univariate splits
- Entropy as the impurity measure
- Information gain for choosing the best split

### 2. 10-Fold Cross Validation
Evaluated the custom decision tree using 10-fold cross-validation. The average classification accuracy was calculated over all folds to assess model generalization.

### 3. Improvement Strategies
Modifications were applied to improve performance:
- **Gini Index**: Replaced entropy with the Gini index for faster and potentially better splits.

## Dataset

- [Wine Quality Dataset (UCI)](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
- Features: 11 numeric attributes representing physicochemical properties of wine
- Label: 0 (quality < 7), 1 (quality ≥ 7)

## File

- `Assignment1_Decision_Trees.ipynb`: Contains full implementation, results, and plots.
