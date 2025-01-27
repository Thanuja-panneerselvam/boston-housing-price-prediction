
# Boston Housing Price Prediction

This project implements a machine learning model to predict housing prices in Boston using various regression techniques. The analysis includes data preparation, model training, evaluation, and visualization of results.

## Features

- Loads and prepares the Boston Housing dataset.
- Creates a correlation heatmap to visualize relationships between features.
- Trains multiple regression models, including Linear Regression and Ridge Regression.
- Evaluates model performance using RMSE and R² metrics.
- Plots predictions against actual values for visual comparison.
- Analyzes feature importance for the trained models.

## Prerequisites

- Python 3.x
- Required Python packages:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

You can install the required packages using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/boston-housing-price-prediction.git
   cd boston-housing-price-prediction
   ```

2. Ensure you have the necessary libraries installed as mentioned in the prerequisites.

## Usage

1. Run the script:

   ```bash
   python boston_housing_prediction.py
   ```

2. The script will load the dataset, train the models, evaluate their performance, and display the results, including:
   - Model performance metrics (RMSE and R²).
   - Feature importance analysis.
   - Correlation heatmap.
   - Plots of predicted vs actual prices.

## Example Output

The script will print the model performance metrics, feature importance, and display visualizations such as the correlation heatmap and prediction plots.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Scikit-learn](https://scikit-learn.org/) for machine learning algorithms.
- [Seaborn](https://seaborn.pydata.org/) and [Matplotlib](https://matplotlib.org/) for data visualization.

