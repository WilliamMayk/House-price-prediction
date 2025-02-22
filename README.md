# House-Price-Prediction

## Project Overview

This project aims to develop a machine learning model to predict house prices based on various features such as location, number of bedrooms, square footage, and other relevant attributes. The dataset used for training and evaluation is stored in 1553768847-housing.csv.
 
## Dataset

- **File:** housing.csv
- **Description:** Contains housing market data, including features that influence house prices.
- **Attributes:** Location, number of bedrooms, number of bathrooms, square footage, lot size, year built, and price.

## Column Description

Here’s the column description in a table format:  

| Column Name            | Description                                               | Data Type  |
|------------------------|-----------------------------------------------------------|------------|
| **longitude**         | The longitudinal coordinate of the house location.        | Float      |
| **latitude**          | The latitudinal coordinate of the house location.         | Float      |
| **housing_median_age** | The median age of the houses in the area.                | Integer    |
| **total_rooms**       | The total number of rooms in the houses within a block.   | Integer    |
| **total_bedrooms**    | The total number of bedrooms in the houses within a block. | Float     |
| **population**        | The total population of the block.                        | Integer    |
| **households**        | The total number of households in the block.              | Integer    |
| **median_income**     | The median income of households in the area (scaled).     | Float      |
| **ocean_proximity**   | Categorical variable indicating proximity to the ocean.   | String     |
| **median_house_value** | The median house price in the area (target variable).     | Integer    |


## Installation

1. Clone the repository:
   ```bash
   git clone <https://github.com/WilliamMayk/House-price-prediction>
   cd house-price-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Data Preprocessing**
   - Load the dataset
   - Handle missing values and outliers
   - Feature scaling and encoding

2. **Model Training**
   - Train different regression models (Linear Regression, Decision Trees, Random Forest, XGBoost)
   - Tune hyperparameters for optimal performance

3. **Model Evaluation**
   - Measure performance using metrics like RMSE, MAE, and R²

4. **Prediction**
   - Use the trained model to predict house prices on new data.

## Dependencies

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

## Future Improvements

- Enhance feature engineering for better accuracy
- Try deep learning models like Neural Networks
- Deploy the model as a web API for real-time predictions

## Author

_William Josue Okwale Mayoukou_  




