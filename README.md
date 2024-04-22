# Stock Price Analysis and Prediction for Vedanta Ltd

![image](https://github.com/Aftabbs/Vedanta-Ltd-Stock-Analysis-And-Prediction/assets/112916888/df339dd4-9fb5-464d-bdf9-1f08544d4fff)

## Overview
This project aims to analyze the historical stock prices of Vedanta Ltd and build a predictive model to forecast future prices. The analysis covers a period of 5 years, with data including opening, high, low, closing prices, adjusted closing prices, and trading volumes.

## Dataset
https://finance.yahoo.com/quote/VEDL.NS

## Methodology
The project follows these steps:

1. **Data Collection**: Gathered historical stock price data for Vedanta Ltd from reliable sources.
2. **Data Preprocessing**: Cleaned and processed the data, handling missing values and ensuring consistency.
3. **Exploratory Data Analysis (EDA)**: Explored the dataset to understand the distribution, trends, and relationships between variables.
4. **Feature Engineering**: Created additional features such as moving averages and daily returns to enhance the predictive power of the model.
5. **Model Selection**: Chose Linear Regression as the final model based on its performance metrics and suitability for the task.
6. **Model Training**: Trained the Linear Regression model using historical stock price data.
7. **Model Evaluation**: Evaluated the model using metrics such as Mean Squared Error (MSE) and R-squared (R2) score to assess its accuracy.
8. **Future Price Prediction**: Utilized the trained model to predict future stock prices for a specified period.

## Assumptions
- The historical stock price data is assumed to be accurate and representative of market conditions.
- The predictive model assumes that past trends and patterns in stock prices will continue into the future.
- External factors such as market news, economic indicators, and company-specific events are not explicitly considered in the model.

## Model Performance
- **Mean Squared Error (MSE)**: 3.2705797802884287
- **R-squared (R2) Score**: 0.9995731538259685

The low MSE value and high R2 score indicate that the Linear Regression model provides accurate predictions for the stock prices of Vedanta Ltd based on the available features.

## Analysis Insights
- **Low Volatility**: The analysis revealed that the stock prices of Vedanta Ltd were less volatile over the analyzed period, indicating relative stability in market performance.
![image](https://github.com/Aftabbs/Vedanta-Ltd-Stock-Analysis-And-Prediction/assets/112916888/058ce106-ee44-4b66-81f2-bbfec2b4d51f)

## Enhancements
- **Feature Engineering**: Further exploration and creation of features, such as sentiment analysis of news articles or macroeconomic indicators, could improve model performance.
- **Advanced Models**: Experimenting with more sophisticated algorithms like Random Forests, Gradient Boosting, or Long Short-Term Memory (LSTM) networks may capture complex patterns in the data.
- **Cross-Validation**: Implementing cross-validation techniques to assess model generalization and robustness.

## Future Work
- **Model Refinement**: Fine-tuning the model hyperparameters and exploring different feature combinations to optimize performance.
- **Real-time Data Integration**: Implementing mechanisms to fetch and incorporate real-time market data for more up-to-date predictions.
- **Deployment**: Developing a user-friendly interface or API to allow stakeholders to interact with the model and receive forecasts seamlessly.

## Dependencies
- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, scikit-learn, fbprophet (for alternative models)

## Usage
1. Clone the repository: `git clone https://github.com/your_username/stock-price-prediction.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Open the Jupyter Notebook: `jupyter notebook`
4. Follow the instructions in the notebook to run the analysis and predict future stock prices.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



































































https://finance.yahoo.com/quote/VEDL.NS
