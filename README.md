# House-Price-Prediction

## Overview

I created this project to predict house prices using various machine learning techniques. The main objective was to develop accurate regression models that can estimate house prices based on different features. I experimented with four machine learning algorithms: Linear Regression, Decision Tree Regressor, Random Forest Regressor, and Gradient Boosting Regressor.

## Motivation

My motivation behind this project was to explore and showcase different regression algorithms for predicting house prices. Through experimentation with different models and preprocessing techniques, I aimed to identify the most accurate approach to effectively predict house prices.

## Technologies Used

- Python
- Libraries: pandas, scikit-learn, matplotlib, seaborn

## Getting Started

1. Clone this repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the Jupyter Notebook `House_Price_Prediction.ipynb` to explore the code, data preprocessing and model building steps.

## Data Preprocessing

- I handled missing values through replacement or elimination.
- I identified and treated outliers.
- Categorical variables were one-hot encoded.
- I split the data into two sets: one with preprocessing and one with preprocessing and log transformation of target variables.

## Model Evaluation

- I applied Linear Regression, Decision Tree Regressor, Random Forest Regressor, and Gradient Boosting Regressor.
- I evaluated the models using Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE) metrics.
- Gradient Boosting Regressor with log-transformed and normalized data yielded the best results.

## Usage

1. Ensure you have the required libraries installed.
2. Run the Jupyter Notebook to see the step-by-step implementation and model evaluation.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for improvements.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any questions or collaborations, please reach out to [your-email@example.com](mailto:your-email@example.com).
