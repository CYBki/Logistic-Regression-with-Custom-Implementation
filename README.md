# Logistic Regression with Custom Implementation

This project implements a simple logistic regression algorithm from scratch using NumPy and Pandas. The dataset used contains breast cancer diagnosis data, and the model predicts whether a tumor is malignant or benign.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Explanation](#model-explanation)
- [Results](#results)
- [Contributing](#contributing)

## Project Overview

The goal of this project is to classify tumors as either malignant (M) or benign (B) using logistic regression. We use gradient descent to optimize the weights and biases of the logistic regression model, and we plot the cost function to track the learning process.

## Installation

To get started, clone this repository to your local machine:

```bash
git clone [https://github.com/your-username/your-repo-name.git](https://github.com/CYBki/Logistic-Regression-with-Custom-Implementation.git)
```

Then, install the required dependencies:

```bash
pip install numpy pandas matplotlib scikit-learn
```

Make sure you have Python 3.10 installed on your machine.

## Usage

1. Load the dataset into your project directory. 
2. Run the script using Python:

```bash
python logistic_regression.py
```

The script reads the data from a CSV file, normalizes it, splits it into training and test sets, and trains the logistic regression model. It also provides accuracy metrics and visualizes the cost function.

## Dataset

The dataset used in this project is a CSV file with breast cancer data. It contains features extracted from digitized images of fine needle aspirates (FNA) of breast masses. The target variable, `diagnosis`, is either 'M' for malignant or 'B' for benign.

## Model Explanation

The logistic regression model is built from scratch using the following steps:

1. **Data Preprocessing**: The features are normalized, and the labels are converted to binary values (1 for malignant, 0 for benign).
2. **Gradient Descent**: The model learns the weights and bias by minimizing the cost function using gradient descent.
3. **Sigmoid Function**: Used to map the output to probabilities between 0 and 1.
4. **Cost Function**: Binary cross-entropy is used as the cost function.

## Results

After training the model for 600 iterations with a learning rate of 4, the following accuracies were achieved:

- **Training Accuracy**: 90.54945054945055 %
- **Test Accuracy**: 94.73684210526316 %

## Contributing

Contributions are welcome! If you would like to improve this project, feel free to fork the repository and submit a pull request.
