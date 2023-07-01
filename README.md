# 📈 Time Series Analysis of JPY, USD, and EUR Currencies

This repository contains the code and analysis for conducting time series analysis on the JPY, USD, and EUR currencies. The main objective of this project is to perform a comparative study of these currencies and develop predictive models using ARIMA modeling and Facebook Prophet. 💹💱

## 📊 Data
The currency data used for the analysis is sourced from reliable financial databases and covers a specific time range. The dataset includes daily exchange rate values for JPY, USD, and EUR.

## 📝 Analysis Steps
1. **Data Preprocessing**: The raw currency data is processed and transformed into a suitable format for time series analysis. Missing values and outliers, if any, are handled appropriately.
2. **Stationarity Analysis**: Stationarity of the time series is checked using statistical tests and visual inspection. If necessary, transformations like differencing are applied to make the series stationary.
3. **Seasonality Analysis**: The presence of seasonality in the time series is analyzed using various techniques such as seasonal decomposition and autocorrelation.
4. **ARIMA Modeling**: ARIMA models are built for each currency to capture the underlying patterns and trends. The models are optimized using techniques like grid search or auto ARIMA.
5. **Facebook Prophet**: The Facebook Prophet library is utilized to develop predictive models for JPY, USD, and EUR currencies. The models leverage trend, seasonality, and holiday effects to forecast future currency values.
6. **Evaluation and Comparative Study**: The performance of the ARIMA models and Facebook Prophet models is evaluated using appropriate metrics. The comparative study helps understand the strengths and limitations of each approach.
7. **Results and Visualizations**: The findings and insights derived from the analysis are presented in the form of visualizations, including time series plots, forecasts, and other relevant graphs.

## 💻 Tech Stack
The main technologies and libraries used in this project are:
- Python 🐍
- ARIMA modeling 📈
- Facebook Prophet 🧙‍♂️
- Pandas 🐼
- NumPy 🔢
- Matplotlib 📊
- Jupyter Notebook 📓

## 🚀 Usage
To run the code and reproduce the analysis, follow these steps:
1. Clone the repository: `git clone https://github.com/amianurag/time-series-analysis.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Open the Jupyter Notebook: `jupyter notebook`
4. Run the notebook cells in sequential order to perform the time series analysis and predictive modeling.

## 📚 Conclusion
This project provides a comprehensive analysis of JPY, USD, and EUR currencies using time series techniques. The results, insights, and predictive models can be utilized for further research, financial forecasting, or decision-making processes related to currency exchange rates.

Please refer to the complete analysis and code in the notebook files for more detailed information.

## 📜 License
This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for your own purposes.

## 🙏 Acknowledgments
We would like to acknowledge the contributions of the open-source community and the developers of the libraries used in this project, which greatly facilitated the analysis and modeling process.
