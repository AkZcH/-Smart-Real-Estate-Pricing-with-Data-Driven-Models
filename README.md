# Housing-Price-Prediction-Model

This project implements a **House Price Prediction Model** using **Linear Regression**. The aim is to predict house prices based on various features such as the number of bedrooms, bathrooms, square footage, and more. The model is trained on historical data and evaluates its performance using metrics like Mean Squared Error (MSE) and R-squared (R²).

## Features
The model uses the following features to make predictions:
- Number of bedrooms
- Number of bathrooms
- Square footage of living space (`sqft_living`)
- Square footage of the lot (`sqft_lot`)
- Number of floors
- Waterfront view (yes/no)
- View score
- Condition of the house
- Square footage above ground (`sqft_above`)
- Square footage of the basement (`sqft_basement`)
- Recent square footage of living space and lot (`sqft_living15`, `sqft_lot15`)

## Workflow
1. **Data Cleaning:** The dataset is cleaned to handle missing values and outliers.
2. **Exploratory Data Analysis (EDA):** Visualizations such as heatmaps and pairplots are used to understand feature correlations.
3. **Model Training:** A Linear Regression model is trained on 80% of the data and tested on the remaining 20%.
4. **Evaluation:** The model’s performance is evaluated using Mean Squared Error (MSE), R-squared (R²), and accuracy of predictions within a tolerance level.
5. **Visualization:** Various visualizations, such as distribution plots and pairplots, are used to assess model accuracy and explore data trends.

## Requirements
- Python 3.x
- Pandas
- Scikit-learn
- Seaborn
- Matplotlib
- NumPy

## Usage
1. Clone this repository.
2. Install the required packages using `pip install -r requirements.txt`.
3. Run the model to predict house prices by executing `main.py`.

## Performance
The model’s accuracy is based on the R-squared score and Mean Squared Error. Continuous improvement is underway to fine-tune feature engineering and model parameters for higher accuracy.

---

This description outlines the project’s purpose, features, workflow, and performance metrics. You can adjust it as needed!
