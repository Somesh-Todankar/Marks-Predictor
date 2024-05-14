# ML Project: Predicting Exam Scores

## Overview

This machine learning project aims to predict students' exam scores based on various features such as gender, race ethnicity, parental level of education, lunch, and test preparation course. The project utilizes multiple regression models and provides a Flask web application for users to input their data and get exam score predictions.

## Project Structure

The project is organized into the following main modules:

- `data_ingestion.py`: Responsible for ingesting raw data and performing train-test split.
- `data_transformation.py`: Handles data preprocessing, imputation, and scaling using the `preprocessor.pkl` file.
- `model_trainer.py`: Trains and evaluates various regression models using train data.
- `predict_pipeline.py`: Loads the pre-trained model and preprocessor for making predictions.
- `app.py`: Flask web application to allow users to input data and get predictions.

## Installation

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AmeyRathi12/ml-project.git



2. Install the required dependencies:
    ```bash
   pip install -r requirements.txt

## Usage

To run the Flask web application and make predictions:


The application will start running on `http://localhost:5000/`.

## Data

The dataset used for this project contains information about students and their exam scores. It is available in the `data` directory as `stud.csv`. The raw data is preprocessed and saved as `data.csv`, and the train and test datasets are stored in `train.csv` and `test.csv`, respectively.

## Models

The project uses the following regression models for predicting exam scores:

- Random Forest Regressor
- Decision Tree Regressor
- Gradient Boosting Regressor
- Linear Regression
- XGBRegressor
- CatBoosting Regressor
- AdaBoost Regressor

## Evaluation

The models are evaluated using the R-squared metric to measure their performance on the test data.

## Predictions

The Flask web application allows users to input their data and get predictions for their exam scores. The application uses the pre-trained `model.pkl` and `preprocessor.pkl` files to make predictions.

## Flask Web Application

The Flask web application (`app.py`) provides a user-friendly interface for users to input their features and get predictions. The application preprocesses the user's input using the `preprocessor.pkl` file and then makes predictions using the pre-trained model from the `model.pkl` file.

## Data Transformation

The `data_transformation.py` module handles data preprocessing, imputation, and scaling before model training. It uses the `preprocessor.pkl` file to transform the data consistently during training and prediction.

## Model Training

The `model_trainer.py` module trains and evaluates various regression models using the train data. The best-performing model is saved as `model.pkl` for later use in predictions.


## Dependencies

- Python 3.x
- Flask
- pandas
- numpy
- scikit-learn
- catboost
- xgboost

## Project Snapshot

![Project Snapshot](https://github.com/AmeyRathi12/ml-project/blob/8b37e1d4892af83c1d545dfa099f2e9a538873b9/Screenshot_20230730_161651.png)

Description: This image shows a snapshot of the working project in action.





## Authors

- Somesh Todankar
- Email: someshtod@gmail.com
- GitHub: (https://github.com/Somesh-Todankar)


