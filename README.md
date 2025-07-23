
# Gold Price Prediction using Random Forest Regressor

This project aims to predict historical gold prices using machine learning techniques, specifically the **Random Forest Regressor**. It leverages time-series and financial indicators to train a model that forecasts future trends in gold pricing.

## Project Description

Gold prices are influenced by various global economic factors. In this project, we analyze a dataset containing historical gold prices along with several economic indicators. After performing Exploratory Data Analysis (EDA), we preprocess the data and build a predictive model using a Random Forest Regressor.

## Machine Learning Model

- **Algorithm**: Random Forest Regressor
- **Evaluation Metrics**: R² Score, Mean Absolute Error (MAE), Mean Squared Error (MSE)
- **Model Features**:
  - Feature selection using correlation matrix
  - Train-test split
  - Hyperparameter tuning
  - Visualization of predicted vs. actual gold prices

## Files Included

- `gold_price_prediction.ipynb`: Main Colab notebook with code and output
- `gold_data.csv`: Historical dataset used
- `README.md`: Project documentation

## Technologies Used

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- Google Colab

## Sample Results

- **R² Score**: 0.94+
- Predicted values closely match real-world price movements
- Insightful visualizations of data trends and feature importance

## Future Work

- Incorporate more global indicators like inflation, interest rate, oil prices
- Try ensemble models like XGBoost or LSTM (for sequence modeling)

## License

This project is open-source and free to use for educational purposes.

---

