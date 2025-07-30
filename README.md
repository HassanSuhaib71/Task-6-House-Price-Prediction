# House Price Prediction

This project demonstrates a machine learning workflow for predicting house prices using Python and scikit-learn. The workflow is implemented in a Jupyter Notebook (`houseprediction.ipynb`) and covers data preprocessing, feature encoding, model training, evaluation, and visualization.

## Features

- Loads and explores housing data from a CSV file
- Encodes categorical features using label encoding
- Splits data into training and test sets
- Scales features for linear regression
- Trains and evaluates both Linear Regression and Gradient Boosting models
- Visualizes actual vs predicted house prices

## Requirements

- Python 3.8+
- Jupyter Notebook
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

Install dependencies with:
```bash
pip install pandas numpy seaborn matplotlib scikit-learn
```

## Usage

1. **Place the dataset**  
   Ensure `Housing.csv` is in the project directory.

2. **Run the notebook**  
   Open `houseprediction.ipynb` in Jupyter Notebook or VS Code and run all cells.

3. **Results**  
   - Model performance metrics (MAE, RMSE) are printed.
   - A scatter plot compares actual and predicted house prices.

## Notes

- If you encounter a `KeyError` for column names, check the actual column names in your CSV using `print(df.columns)` and update the notebook accordingly.
- You can experiment with different models or preprocessing steps for improved accuracy.

## License

This project is for educational purposes.