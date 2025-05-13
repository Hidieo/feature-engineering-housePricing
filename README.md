# Predictive House Pricing

This project contains a Jupyter Notebook that demonstrates how to build a machine learning model for predicting house prices. The notebook walks through the process of data exploration, preprocessing, feature engineering, model training, evaluation, and prediction. The goal is to predict house prices based on various features such as area, size, number of rooms, and other relevant factors.

## Requirements

To run this notebook, you'll need to install the dependencies listed below. You can install them using `pip`.

### Installation with pip:

```bash
pip install -r requirements.txt
```

## Dataset

The dataset used in this project is a house pricing dataset containing information about various houses, including features like the number of bedrooms, square footage, and other factors that could affect house prices.

- **Column Features**: Includes features such as `area`, `bedrooms`, `bathrooms`, `guestrooms`, `basement`, `parking`, etc.
- **Target Variable**: `price`, which is the price of the house.

## Files

- `Feature_Engineering_DSF_39_0.ipynb`: The main Jupyter Notebook containing the analysis, model training, evaluation, and predictions for house pricing.
- `requirements.txt`: A list of Python dependencies for the project.
- `house_dataset.zip` : A dataset

## How to Use

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/Hidieo/predictive-house-pricing.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Run the cells in the notebook to replicate the data analysis, preprocessing, training, and prediction steps.

5. Or, you can visit my Google Colab for this Machine Learning: https://colab.research.google.com/drive/1G9uzHQY6u0-9Hkx3Dnjj-arNxGTFeKJY?authuser=0#scrollTo=N8x1zAHMl_IF

## Model and Evaluation

In this project, I use a **RandomForestRegressor** model to predict house prices. The model is evaluated using various metrics:

- **R²**: Indicates how well the model explains the variability of house prices.
- **RMSE (Root Mean Squared Error)**: Measures the average magnitude of the errors, giving higher weight to large errors.
- **MAE (Mean Absolute Error)**: Indicates the average absolute difference between predicted and actual prices.

### Model Performance:

- **R² Mean**: 0.9716
- **R² Std Dev** : 0.009651522506931626
- **RMSE**: 356,725.05
- **MAE**: 212,588.57

The notebook also includes visualizations like scatter plots and residual plots to assess model performance and detect any systematic errors in the predictions.

## Results and Insights

- The model provides **good predictions**, with high R² values indicating that the model explains a large portion of the variability in house prices.
- The residuals show that there are some discrepancies, but overall the model performs well in predicting the house prices based on the given features.
- Visualizations help in assessing model accuracy and identifying any potential outliers or biases.
