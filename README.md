# Credit Card Fraud Detection

This project uses machine learning models to detect credit card fraud.

## Project Structure

- **data/**: Directory to store the dataset.
- **notebooks/**: Jupyter Notebooks for exploratory data analysis (EDA).
- **models/**: Directory to save trained models.
- **src/**: Directory for source code.
- **requirements.txt**: File listing the dependencies required for the project.
- **README.md**: Documentation for the project.

## How to Run

1. Clone the repository:
    ```
    git clone <your-github-repo-url>
    cd credit_card_fraud_detection
    ```

2. Install the dependencies:
    ```
    pip install -r requirements.txt
    ```

3. Run the training script:
    ```
    python src/train_model.py
    ```

## Models

The trained models are saved in the `models/` directory.

- Logistic Regression: `models/logistic_regression_model.pkl`
- Multi-Layer Perceptron: `models/mlp_model.pkl`
