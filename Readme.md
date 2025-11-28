# Income Prediction Using Multilayer Perceptron (MLP)

This project demonstrates the development of a **multilayer perceptron (MLP) model** for predicting whether an individual earns above or below $50,000 per year based on demographic data. The dataset used is substantially imbalanced, with a **75:25 ratio** between the majority and minority classes.

## Key Features

- **Multilayer Perceptron (MLP)** architecture designed for tabular demographic data.
- **Robustness and generalization improvements** implemented using:
  - **Class weighting** to address class imbalance.
  - **L2 regularization (weight decay)** to prevent overfitting.
  - **Dropout layers** for further regularization.
  - **Batch normalization** to stabilize and accelerate training.
- Achieved a **significant performance boost**, raising AUROC from **81% to 91%**.

## Performance Metrics

- AUROC: 91%
- Precision, Recall, and F1-score optimized using threshold tuning.
- Effective handling of imbalanced classes through weighted loss.

## Usage

1. Preprocess the demographic dataset.
2. Define the MLP architecture with normalization and dropout layers.
3. Train the network using **AdamW optimizer** and minibatch gradient descent.
4. Evaluate on the test set with metrics including AUROC, precision, recall, and F1-score.

This project demonstrates practical techniques for improving neural network performance on **imbalanced tabular datasets** and can serve as a template for similar predictive modeling tasks.
