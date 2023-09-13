# Stock Price Prediction

## Project Description

The Stock Price Prediction project aims to predict future stock prices using historical stock market data. This predictive model utilizes Linear Regression, a machine learning technique, to forecast the closing price of a particular stock.
By analyzing historical trends and patterns in stock market data, this project provides insights into potential future price movements.

## Dataset Description

The dataset, named INR=X.csv, contains historical stock market data in a tabular format. It includes the following columns:

- **Date**: The date of the stock market data in "YYYY-MM-DD" format.
- **Open**: The opening price of the stock on a specific date.
- **High**: The highest price of the stock reached during the day.
- **Low**: The lowest price of the stock reached during the day.
- **Close**: The closing price of the stock on a specific date.
- **Adj Close**: The adjusted closing price of the stock on a specific date, accounting for factors like dividends and stock splits.
- **Volume**: The trading volume of the stock on a specific date, representing the number of shares traded.

## Model Selection

In this project, I experimented with two machine learning models: Linear Regression and Support Vector Regression (SVR). After rigorous evaluation, the Linear Regression model emerged as the best-performing model for stock price prediction. 
It demonstrated superior accuracy in forecasting future stock prices based on historical data.

## Usage

To use this project for stock price prediction:

1. **Dataset**: Download the dataset from this [link](https://drive.google.com/drive/folders/10p_Rc36Uq_1vP31mTHqHfjHnd0cObG0m) and place it in the project directory.

2. **Dependencies**: Ensure you have the required Python packages installed by running `pip install -r requirements.txt`.

3. **Model Training**: Run the Jupyter Notebook or Python script to train the Linear Regression model on the historical stock data.

4. **Predictions**: Use the trained model to make stock price predictions. You can provide input features such as the opening price, highest price, lowest price, and trading volume to obtain predictions for future closing prices.

5. **Evaluation**: Assess the model's performance using appropriate evaluation metrics, such as Mean Absolute Error (MAE) or Mean Squared Error (MSE), to gauge the accuracy of your predictions.

## Future Improvements

While the Linear Regression model has shown promising results, there's room for improvement in this project. Future enhancements may include:

- Experimenting with more advanced time series forecasting models, such as ARIMA or LSTM.
- Incorporating additional features or external factors that may influence stock prices, such as economic indicators, news sentiment, or market sentiment.
- Developing a user-friendly web application or dashboard for users to easily access and visualize stock price predictions.

## Contact Information

If you have any questions, suggestions, or feedback, please don't hesitate to reach out:

- Email: bansal.pra2000@gmail.com
- Linkedin: https://www.linkedin.com/in/pranavbansal0609

Feel free to contribute to this project or use it as a starting point for your stock price prediction endeavors.

