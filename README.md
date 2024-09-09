# agricultural-predictions
 Attempting to predict agricultural yields and commodities prices with a variety of predictors and models

## Project Overview

This project aims to predict agricultural yields and the prices of agricultural commodities using a diverse set of predictors. The analysis is conducted using Jupyter Notebooks and leverages various data sources to model complex relationships between environmental factors, market conditions, and agricultural outcomes.

### Key Objectives:
- **Predict Agricultural Yields:** Using predictors like weather, climate patterns, satellite imagery, pest levels, and potentially unconventional factors such as the moon cycle.
- **Predict Commodity Prices:** Extending the model to predict agricultural commodity prices, incorporating market-related factors in addition to the predictors used for yield prediction.

## Data Sources

- **Weather Data:** Historical and forecasted weather conditions.
- **Climate Data:** Long-term climate patterns and anomalies.
- **Satellite Imagery:** Remote sensing data for monitoring crop health, vegetation indices, and more.
- **Pest Levels:** Data on pest populations and their impacts on crops.
- **Moon Cycle:** Data related to lunar phases to explore potential correlations with agricultural outcomes.
- **Market Data:** Historical prices, supply and demand, and other relevant economic indicators for agricultural commodities.

## Project Structure

- **data/**: Directory containing raw data files.
- **notebooks/**: Jupyter notebooks used for data exploration, feature engineering, model training, and evaluation.
- **models/**: Trained models and scripts for model training and inference.
- **results/**: Output files, including visualizations and model performance metrics.
- **requirements.txt**: Python dependencies for running the project.
- **README.md**: This document.

## Notebooks

1. **Data Exploration and Preprocessing:** Initial exploration of datasets, cleaning, and preprocessing steps.
2. **Feature Engineering:** Creating new features from raw data to improve model performance.
3. **Modeling Agricultural Yields:** Training and evaluating models to predict yields using various predictors.
4. **Modeling Commodity Prices:** Applying similar techniques to predict prices of agricultural commodities.
5. **Unconventional Predictors:** Investigating the impact of less traditional predictors, such as the moon cycle.

## Dependencies

Ensure you have the following Python packages installed:

```plaintext
numpy
pandas
scikit-learn
matplotlib
seaborn
xgboost
lightgbm
jupyter
```

You can install them using:

```bash
pip install -r requirements.txt
```

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/agriculture-yield-prediction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd agriculture-predictions
    ```
3. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
5. Open the notebooks in the `notebooks/` directory and follow along with the analysis.

## Results

- **Agricultural Yield Predictions:** Results of yield prediction models, including accuracy, precision, recall, and other relevant metrics.
- **Commodity Price Predictions:** Analysis of price prediction models, along with evaluation metrics and insights.

## Future Work

- Explore additional predictors, including more granular market data.
- Integrate real-time data sources for dynamic predictions.
- Experiment with different modeling techniques and ensemble methods.
- Publish results and potentially create a dashboard for real-time yield and price predictions.

## Contributing

Contributions are welcome! Please submit a pull request with a clear description of your changes.

## License

This project is licensed under the MIT License.
