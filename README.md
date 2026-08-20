# Human-in-the-Loop Machine Learning

This project explores a **human-in-the-loop (HITL) machine learning workflow**, where human feedback is incorporated iteratively to improve model training and evaluation.

The analysis demonstrates how labeled data can be expanded through an iterative process of sample selection, human labeling, model training, and evaluation.

## Workflow

The project follows an iterative HITL pipeline:

1. Select samples for human labeling
2. Collect and organize labels
3. Split labeled data into training and testing sets
4. Train a machine learning model
5. Evaluate model performance
6. Use evaluation results to inform subsequent labeling

## Analysis

The project includes:

- Sample selection for human labeling
- Label management and selection tracking
- Training/test data preparation
- Machine learning model training
- Model evaluation
- Analysis of iterative labeling results

## Methods

**Human-in-the-Loop Learning**
- Iterative data labeling
- Sample selection
- Human feedback

**Machine Learning**
- Supervised learning
- Model training and evaluation

## Tools

- Python
- pandas
- scikit-learn
- Jupyter Notebook

## Repository Structure

```text
├── to_label/          # Samples selected for labeling
├── selection_log/     # Records of sample selection
├── train_test/        # Training and testing data
├── evaluate/          # Evaluation outputs
├── eval/              # Evaluation resources
├── human_in_the_loop_classification.ipynb            # Analysis notebook
└── README.md

```
## Context

This project was completed as coursework for DA 351: Advanced Descriptive Methods at Denison University.
