
- **Breast Cancer Logistic Regression.ipynb**: Jupyter notebook containing the implementation of the logistic regression model, including data preprocessing, model training, and evaluation.
- **Breast Cancer Wisconsin (Diagnostic) Data Set.csv**: Dataset used for training and evaluating the model.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/AbdooMohamedd/breast-cancer-logistic-regression.git
    cd breast-cancer-logistic-regression
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```sh
    pip install pandas seaborn matplotlib scikit-learn
    ```

## Usage

1. Open the Jupyter notebook:
    ```sh
    jupyter notebook Breast Cancer Logistic Regression.ipynb
    ```

2. Run the cells in the notebook to preprocess the data, train the logistic regression model, and evaluate its performance.

## Evaluation Metrics

The following metrics are used to evaluate the performance of the logistic regression model:

- **Accuracy**: Measures the proportion of correctly classified instances.
- **Precision**: Measures the proportion of true positive instances among the instances classified as positive.
- **Recall**: Measures the proportion of true positive instances among the actual positive instances.
- **F1 Score**: Harmonic mean of precision and recall.

## Results

The results of the model evaluation are printed in the notebook:

```python
# Metrics
accuracy = accuracy_score(y_test, y_pred)
precision = precision_score(y_test, y_pred)
recall = recall_score(y_test, y_pred)
f1 = f1_score(y_test, y_pred)

print(f"Accuracy: {accuracy:.2f}")
print(f"Precision: {precision:.2f}")
print(f"Recall: {recall:.2f}")
print(f"F1 Score: {f1:.2f}")