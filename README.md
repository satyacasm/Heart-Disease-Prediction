# Heart Disease Prediction

This repository contains code and resources for predicting heart disease using machine learning and deep learning techniques. The project utilizes the Cleveland Heart Disease dataset and the Statlog (Heart) dataset to train and evaluate models for predicting the presence of heart disease.

## Table of Contents

- [Introduction](#introduction)
- [Datasets](#datasets)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Heart disease is one of the leading causes of death globally. Early detection and prevention are crucial in reducing mortality rates. This project aims to develop a predictive model using machine learning and deep learning techniques to identify individuals at risk of heart disease.

## Datasets

### Cleveland Heart Disease Dataset
The Cleveland dataset is a well-known dataset for heart disease prediction and contains 303 instances with 14 attributes, including age, sex, chest pain type, resting blood pressure, serum cholesterol, fasting blood sugar, resting ECG results, maximum heart rate achieved, exercise-induced angina, oldpeak, the slope of the peak exercise ST segment, number of major vessels colored by fluoroscopy, thalassemia, and the presence of heart disease (target).

### Statlog (Heart) Dataset
The Statlog dataset contains 270 instances with the same attributes as the Cleveland dataset, making it suitable for combining and cross-validation.

## Installation

To run the project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/satyacasm/Heart-Disease-Prediction.git
    cd Heart-Disease-Prediction
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Ensure you have the datasets (`Heart_disease_cleveland_new.csv` and `heart.dat`) in the project directory.

2. Run the script to train and evaluate the models:
    ```sh
    python main.py
    ```

3. The results will be saved in the `model_results.csv` file.

## Model

The project includes the following steps:

1. **Data Preprocessing**: Load and preprocess the Cleveland and Statlog datasets.
2. **Feature Scaling**: Normalize the feature values using StandardScaler.
3. **Model Training**: Train a neural network using the Jellyfish Optimization Algorithm to find the best hyperparameters.
4. **Model Evaluation**: Evaluate the model on a test set using metrics such as accuracy, precision, recall, F1 score, and ROC AUC score.

## Results

The results of the model, including accuracy, precision, recall, F1 score, and ROC AUC score, are saved in the `model_results.csv` file.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add your message here'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
