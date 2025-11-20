# Urban Building Energy Rating Prediction 🏢⚡

## Project Overview
This project aims to develop a machine learning system to predict the **Simple Building Energy Rating** (A, B, C) of urban buildings based on various parameters such as insulation values, building type, and environmental factors. An Artificial Neural Network (ANN) is implemented to perform this multi-class classification task.

## Dataset
The dataset used in this project is the **Urban building energy performance prediction and retrofit analysis** dataset from Mendeley Data.
* **Source:** [Mendeley Data](https://data.mendeley.com/datasets/m6vv9k9gcd/5)
* **Size:** ~1 Million records
* **Target Variable:** `Simple_Building_Energy_Rating`

## Project Flow
1.  **Data Preprocessing:** Cleaning, handling missing values, and feature scaling.
2.  **EDA:** Exploratory Data Analysis to understand feature distributions.
3.  **Modeling:** Building and training an ANN model using TensorFlow/Keras.
4.  **Evaluation:** Assessing performance using Accuracy, F1-Score, Confusion Matrix, and Cohen’s Kappa.

## Technologies Used
* Python 3.x
* Pandas & NumPy
* TensorFlow & Keras
* Scikit-learn
* Matplotlib & Seaborn

## Installation
1.  Clone the repository:
    ```bash
    git clone [https://github.com/yourusername/urban-building-energy-prediction.git](https://github.com/yourusername/urban-building-energy-prediction.git)
    ```
2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
