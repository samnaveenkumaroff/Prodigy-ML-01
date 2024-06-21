# Prodigy-ML-01
A linear regression model to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms.
README file:
---

# House Price Prediction with Linear Regression

## Overview

This project implements a linear regression model to predict house prices based on square footage, number of bedrooms, and bathrooms. The model utilizes the "House Prices: Advanced Regression Techniques" dataset from Kaggle, which includes features like living area, bedrooms above ground, bathrooms, and sale prices.

## Requirements

- Python 3.x
- Libraries:
  - pandas
  - numpy
  - scikit-learn

## Installation

1. Install required libraries:

   ```bash
   pip install -r requirements.txt
   ```

2. Download the dataset from Kaggle:
   - Register or log in to Kaggle and download the dataset files (`train.csv` and `test.csv`) from [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data).
   - Place the downloaded files in the project directory.

## Usage

1. Run the Jupyter notebook `Prodigy-ML-01.ipynb` or execute the Python script `Prodigy-ML-01.py`.
   
   ```bash
   jupyter notebook Prodigy-ML-01.ipynb
   ```

   or

   ```bash
   python Prodigy-ML-01.py
   ```

2. Follow the instructions in the notebook/script to:
   - Load and preprocess the dataset.
   - Train a linear regression model using features (`GrLivArea`, `BedroomAbvGr`, `FullBath`) to predict house prices (`SalePrice`).
   - Evaluate the model's performance using metrics like Mean Squared Error (MSE) and R-squared.
   - Make predictions for new data points.

## File Descriptions

- `Prodigy-ML-01.ipynb`: Jupyter notebook containing the implementation of the linear regression model.
- `Prodigy-ML-01.py`: Python script for the same implementation as the notebook.
- `train.csv`: Dataset used for training the model.
- `test.csv`: Dataset used for testing the model.
- `README.md`: This file, providing an overview of the project, installation instructions, usage guide, and file descriptions.

## Credits

Crafted With Love by **Sam Naveenkumar .V**

- Kaggle for providing the "House Prices: Advanced Regression Techniques" dataset.
- [Scikit-learn](https://scikit-learn.org/) and [Pandas](https://pandas.pydata.org/) libraries for their machine learning and data manipulation functionalities.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---
