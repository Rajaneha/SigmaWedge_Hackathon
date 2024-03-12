# SigmaWedge_Hackathon

List of Stocks

|Sid             |Symbol    | Exchange           | Name              | Delisted |
|----------------|----------|--------------------|-------------------|----------|
| FIBBG000B9XRY4 | AAPL     | XNAS               | APPLE INC         | False    |
| FIBBG000BKZB36 | HD       | XNYS               | HOME DEPOT INC    | False    |
| FIBBG000BMHYD1 | JNJ      | XNYS               | JOHNSON & JOHNSON | False    |
| FIBBG000BPH459 | MSFT     | XNAS               | MICROSOFT CORP    | False    |
| FIBBG000GZQ728 | XOM      | XNYS               | EXXON MOBIL CORP  | False    |


#### Getting Apple Stock Data for 2023
To obtain only the Apple stock data for the year 2023 (from January 1, 2023, to December 31, 2023), follow these steps:

1. **Filtering by Symbol and Date**: Use the filtering capabilities of your data analysis tool or programming language to select rows where the 'Symbol' column equals 'AAPL' and the 'Date' column falls within the range of January 1, 2023, to December 31, 2023.
2. **Exporting or Displaying Results**: After filtering, export or display the filtered data containing only the Apple stock data for the year 2023.

Adjust the filtering criteria and methodology according to your specific data analysis tool or programming language.

#### Stock Prices

| Field        | Date          | FIBBG000B9XRY4 |
|--------------|---------------|----------------|
| Close        | 2023-01-03    | 124.2163       |                 
| Close        | 2023-01-04    | 125.4975       |                 
| Close        | 2023-01-05    | 124.1666       |                 
| Close        | 2023-01-06    | 128.7352       |                 
| Close        | 2023-01-09    | 129.2616       |   


#### Model Results
#### Final Portfolio Value
The final portfolio value is 17.

#### Transition Distribution
The transition distribution matrix is represented as follows:

|         | Bear      | Flat      | Bull      |
|---------|-----------|-----------|-----------|
| Bear    | 0.142857  | 0.742857  | 0.114286  |
| Flat    | 0.146497  | 0.598726  | 0.254777  |
| Bull    | 0.125     | 0.678571  | 0.196429  |

This matrix represents the probabilities of transitioning from one state to another.


# Forecasting Techniques
#### Forecasting Using ARIMA
ARIMA (AutoRegressive Integrated Moving Average) is a popular time series forecasting technique. To forecast using ARIMA:

1. **Data Preprocessing**: Preparing  time series data by checking for stationarity, differencing if necessary, and splitting into training and testing datasets.
2. **Model Selection**: Choose appropriate ARIMA parameters (p, d, q).
3. **Model Fitting**: Fit the ARIMA model to the training data using selected parameters.
4. **Forecasting**: Used the fitted model to forecast future values.

## Forecasting Values using Linear Regression
Linear Regression is a simple and widely used technique for forecasting. To forecast using Linear Regression:

1. **Data Preparation**: Preparing dataset by selecting relevant features and splitting into training and testing datasets.
2. **Model Training**: Train a Linear Regression model.
3. **Model Evaluation**: Evaluate the model's performance.
4. **Forecasting**: Used the trained model to forecast future values.

## Finding the Optimal Buy Indices and Portfolio Value after Forecasting
After forecasting future values, we can use various optimization techniques to find the optimal buy indices and maximize portfolio value. 
