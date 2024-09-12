# Decision Tree Classifier for Bank Marketing Data

This repository contains a project that builds a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data using the Bank Marketing dataset.

## Table of Contents
1. [Project Description](#project-description)
2. [Installation](#installation)
3. [Dataset](#dataset)
4. [Code and Analysis](#code-and-analysis)
5. [Results](#results)
6. [How to Run](#how-to-run)
7. [License](#license)

## Project Description
The project involves:
- Performing data cleaning and preprocessing on the Bank Marketing dataset.
- Building a decision tree classifier to predict customer purchase decisions.
- Evaluating the model's performance and visualizing the results.

## Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/decision-tree-classifier-bank-marketing.git
    ```
2. Navigate into the project directory:
    ```bash
    cd decision-tree-classifier-bank-marketing
    ```
3. Install the required Python libraries using:
    ```bash
    pip install -r requirements.txt
    ```

## Dataset
The dataset used for this project is the Bank Marketing dataset, which can be downloaded from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing). If included, the dataset file is `bank.csv`.

## Code and Analysis
The notebook (`.ipynb`) and Python script (`.py`) files include the code for:
- Data Cleaning:
  - Handling missing values.
  - Encoding categorical variables.
- Building and training the Decision Tree Classifier.
- Evaluating the model:
  - Classification report.
  - Accuracy score.
- Visualizations:
  - Confusion Matrix.
  - Feature Importance.

## Results
Key visualizations from the analysis include:
- **Confusion Matrix**:
  ![Confusion Matrix](confusion_matrix.png)
- **Feature Importance**:
  ![Feature Importance](feature_importance.png)

## How to Run
1. To run the project, open the `decision_tree_classifier.ipynb` file in Google Colab or Jupyter Notebook and execute the cells step-by-step.
2. If using the Python script:
    ```bash
    python decision_tree_classifier.py
    ```

## License
This project is licensed under the MIT License.
