# SP500 Value Investing - Data Preprocessing

A machine learning-based tool for identifying undervalued stocks in the S&amp;P 500, leveraging Benjamin Graham's value investing principles. In this phase, we've completed data preprocessing to prepare the dataset for model development.

## Introduction

This project applies machine learning techniques to the domain of stock market investing, specifically focusing on the S&amp;P 500 index. By analyzing historical financial data and utilizing the principles of value investing as outlined by Benjamin Graham, this tool aims to identify potentially undervalued stocks that may offer favorable investment opportunities.

## Intended Features

Historical Data Analysis: Uses data from the past 5 years to train the model.

Value Investing Metrics: Applies key metrics like P/E ratio, P/B ratio, and dividend yield.

Machine Learning Prediction: Employs machine learning algorithms to forecast stock price trends.

Investment Insights: Provides insights into potential stock investments based on model predictions.

## Data Preprocessing

In this stage, we've performed the following data preprocessing steps:

- **Data Retrieval**: Obtained relevant values from yfinance
- **Data Cleaning**: Removed missing values and handled outliers.

## Data Sources

The dataset used in this project was obtained via the yfinance library, which provides access to financial data from Yahoo Finance. It consists of financial metrics such as PE Ratio, PB Ratio, Dividend Yield, Debt-to-Equity Ratio, Current Ratio, and Earnings Yield, which are essential for our project's financial analysis and modeling.

## Dependencies

To recreate the environment and run the preprocessing code, you'll need the following Python libraries and packages:

- `numpy==1.19.5`
- `pandas==1.3.3`
- `pandas-datareader==0.9.0`
- `matplotlib==3.4.3`
- `seaborn==0.11.2`
- `yfinance==0.1.63`
- `scikit-learn==0.24.2`

You can install these dependencies using `pip install -r requirements.txt`.

## Results

While the focus of this phase was data preprocessing, initial data analysis and visualizations was conducted.

Among the findings, the most prominent linear correlation observed was -0.51, which signifies a weak negative linear relationship between two of the features (earnings yield and P/E ratio). Additionally, a mode value of 20 for the P/E ratio was identified, a characteristic often associated with overvaluation in line with Benjamin Graham's principles from _The Intelligent Investor_.

## Next Steps

The next steps in this project include:

- Feature selection
- Building and training machine learning models.
- Evaluating model performance using appropriate metrics.
- Deploying the project.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact Information

If you have questions or would like to collaborate, feel free to reach out to Tan Dexter at [tandexter98@gmail.com](mailto:tandexter98@gmail.com).
