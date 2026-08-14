# Rainfall Prediction ML

A machine learning-based system for predicting whether rainfall will occur using historical meteorological and weather-related data. The project compares **Decision Tree** and **Random Forest** classification models and evaluates their performance using multiple classification metrics.

## Project Overview

Rainfall prediction is an important application of machine learning that can support agricultural planning, weather analysis, water resource management, and climate-related decision-making.

This project develops a **Rain/No Rain classification system** using historical weather data. The workflow includes data preprocessing, model training, prediction, evaluation, and visualization using Python and machine learning libraries.

## Objectives

- Analyze historical weather data for rainfall prediction.
- Preprocess and prepare the dataset for machine learning.
- Develop classification models for Rain/No Rain prediction.
- Compare the performance of Decision Tree and Random Forest models.
- Evaluate the models using accuracy, precision, recall, and F1-score.
- Visualize model performance and prediction results.

## Technologies Used

- **Programming Language:** Python
- **Development Environment:** Google Colab
- **Libraries:**
  - NumPy
  - Pandas
  - Scikit-learn
  - Matplotlib
  - Seaborn
- **Version Control:** GitHub

## Dataset

The project uses a historical rainfall/weather dataset containing meteorological features such as:

- Pressure
- Maximum Temperature
- Temperature
- Minimum Temperature
- Dew Point
- Humidity
- Cloud Cover
- Sunshine
- Wind Direction
- Wind Speed
- Rainfall (target variable)

The dataset is available in the `dataset/` directory as `Rainfall.csv`.

## Data Preprocessing

The dataset is prepared before model training through the following steps:

1. Loading the rainfall dataset using Pandas.
2. Inspecting the dataset and identifying relevant features.
3. Handling missing values using appropriate preprocessing techniques.
4. Separating input features and the target variable.
5. Encoding categorical values where required.
6. Splitting the dataset into training and testing sets.
7. Scaling numerical features where applicable.

## Models Used

### 1. Decision Tree Classifier

A Decision Tree classifier is used as a baseline classification model. It makes predictions by creating a tree-like structure based on feature values and decision rules.

### 2. Random Forest Classifier

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction performance and generalization.

The performance of both models is compared using standard classification metrics.

## Results

The models were evaluated using accuracy, precision, recall, and F1-score.

| Model | Accuracy |
|---|---:|
| Decision Tree | Compared during evaluation |
| Random Forest | **79.72%** |

The **Random Forest model achieved an accuracy of 79.72%** and demonstrated strong overall classification performance.

### Random Forest Evaluation Metrics

- **Accuracy:** 79.72%
- **Precision:** 80.70%
- **Recall:** 92.00%
- **F1-Score:** 85.98%

The high recall indicates that the Random Forest model was effective at identifying rainfall cases.

## Evaluation Metrics

The following metrics were used to evaluate model performance:

- **Accuracy:** Measures the overall percentage of correct predictions.
- **Precision:** Measures how many predicted rainfall cases were actually rainfall cases.
- **Recall:** Measures how many actual rainfall cases were correctly identified.
- **F1-Score:** Provides a balance between precision and recall.
- **Confusion Matrix:** Visualizes correct and incorrect predictions for each class.

## How to Run

### Option 1: Google Colab

1. Open `Rainfall_Prediction_system.ipynb`.
2. Click **Open in Colab**.
3. Make sure the dataset is available in the expected location.
4. Run the notebook cells sequentially.
5. View the model predictions, evaluation metrics, and visualizations.

### Option 2: Local Environment

Clone the repository:

```bash
git clone https://github.com/Pranathipasapu/Rainfall-Prediction-ML.git
