# MAGIC Gamma Telescope Dataset Classification

This project demonstrates the use of different machine learning models to classify data from the MAGIC Gamma Telescope dataset. The dataset contains measurements from a gamma-ray telescope and consists of data points classified as either `gamma` or `hadron`.

## Dataset
The MAGIC Gamma Telescope dataset is publicly available and can be accessed via the [UCI Machine Learning Repository](https://doi.org/10.24432/C52C8B).

- **Features**: 10 features describing the measurements.
- **Class**: Binary classification of the target variable ('g' for gamma, 'h' for hadron).

## Models Implemented
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Logistic Regression
- Support Vector Machine (SVM)
- Neural Network (using TensorFlow)

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/debargyadinda/magic_gamma_Dataset.git
    cd magic_gamma_Dataset
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Download the dataset from [here](https://archive.ics.uci.edu/ml/datasets/MAGIC+Gamma+Telescope).
2. Place the dataset in the `data` folder.
3. Run the following code to train and evaluate the models:

    ```bash
    python src/main.py
    ```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
