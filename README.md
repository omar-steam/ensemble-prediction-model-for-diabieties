# Diabetes Prediction Using Ensemble Model

## Overview
This project implements an ensemble machine learning model to predict diabetes based on health metrics. The model combines **Random Forest** and **Gradient Boosting** classifiers using a **Voting Classifier** to achieve better accuracy and generalization.

## Features
- **Dataset**: The dataset contains 768 entries and 9 features such as glucose levels, BMI, and age.
- **Algorithms**:
  - **Random Forest**: A bagging technique for stability and reduced overfitting.
  - **Gradient Boosting**: A boosting technique for capturing complex patterns.
- **Ensemble Technique**: Soft voting to combine the strengths of both algorithms.

## Results
- **Accuracy**: ~75% on the test dataset.
- **Metrics**: Includes precision, recall, F1-score, and confusion matrix.
- **Visualizations**:
  - Correlation Heatmap: Highlights relationships between features.
  - Confusion Matrix: Displays classification results.

## Usage
1. Clone this repository and upload the `diabetes.csv` dataset.
2. Open `ensemble-prediction-model-for-diabieties.ipynb` in Google Colab or Jupyter Notebook.
3. Execute all cells to train the model and view the results.

## Requirements
- Python 3.7 or higher
- Libraries:
  - `pandas`
  - `seaborn`
  - `matplotlib`
  - `sklearn`

## License
This project is open-source and available under the MIT License.







