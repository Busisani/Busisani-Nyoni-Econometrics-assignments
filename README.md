# Financial Econometrics Project: Volatility Modeling Challenges

##  Overview
This project delves into key statistical and econometric challenges encountered in financial time series modeling, specifically using Apple Inc. (AAPL) stock data from 2018–2025. It highlights common issues such as multicollinearity, skewness, outliers, and overfitting, demonstrating their impact and potential mitigation strategies within the context of financial data.

##  Objective
The primary objective is to develop a structured framework for identifying, diagnosing, and mitigating these challenges, culminating in the application of volatility modeling (GARCH) to capture the dynamic nature of financial risk.

##  Topics Covered
-   **Multicollinearity**: Analyzing relationships between predictor variables.
-   **Skewness**: Examining the asymmetry of return distributions.
-   **Outliers**: Identifying and understanding extreme market events.
-   **Overfitting**: Assessing model generalization capability.
-   **Volatility Modeling (GARCH)**: Capturing time-varying volatility clustering.

##  Dataset
-   **Asset**: Apple Inc. (AAPL) stock data.
-   **Source**: Yahoo Finance.
-   **Period**: January 1, 2018, to December 31, 2025.
-   **Data Type**: Log returns are calculated for all analyses to ensure consistency.

##  Tools Used
-   **Python**: Programming language.
-   **`yfinance`**: For fetching historical stock data.
-   **`pandas`**: For data manipulation and analysis.
-   **`numpy`**: For numerical operations.
-   **`matplotlib` & `seaborn`**: For data visualization.
-   **`scipy.stats`**: For statistical functions (e.g., skewness, z-scores).
-   **`statsmodels`**: For statistical modeling and diagnostics (e.g., VIF).
-   **`scikit-learn`**: For machine learning tasks (e.g., train-test split, linear regression).
-   **`arch`**: For advanced econometric models, specifically GARCH.

##  Key Findings
-   Financial return series consistently exhibit non-normality, including skewness and significant outliers.
-   Volatility in financial markets is not constant but demonstrates clustering, necessitating advanced models like GARCH.
-   Robust statistical techniques and careful model validation are crucial to mitigate the risks associated with multicollinearity, outliers, and overfitting, leading to more reliable financial models.
-   Ignoring these challenges can lead to biased estimates, poor forecasts, and significant financial losses in practice.

##  How to Run
1.  **Open Google Colab**: Upload the `.ipynb` notebook file to your Google Drive or open it directly in Colab.
2.  **Install Libraries**: Ensure all required Python libraries are installed (e.g., by running the `!pip install` cell).
3.  **Run All Cells**: Execute all cells sequentially to reproduce the analysis, visualizations, and results.

##  References

### Data Source
*   Yahoo Finance. “Apple Inc. (AAPL) Historical Data.” Yahoo Finance, `https://finance.yahoo.com/quote/AAPL/history/`.

### Core Econometrics & Regression
*   Wooldridge, Jeffrey M. *Introductory Econometrics: A Modern Approach*. 5th ed., Cengage Learning, 2015.
*   Gujarati, Damodar N., and Dawn C. Porter. *Basic Econometrics*. 5th ed., McGraw-Hill, 2009.
*   Stock, James H., and Mark W. Watson. *Introduction to Econometrics*. 3rd ed., Pearson, 2011.

### Financial Time Series & Volatility
*   Tsay, Ruey S. *Analysis of Financial Time Series*. 3rd ed., Wiley, 2010.
*   Bollerslev, Tim. “Generalized Autoregressive Conditional Heteroskedasticity.” *Journal of Econometrics*, vol. 31, no. 3, 1986, pp. 307–327.
*   Engle, Robert F. “Autoregressive Conditional Heteroskedasticity with Estimates of the Variance of UK Inflation.” *Econometrica*, 1982.

### Statistical Concepts (Skewness, Outliers, Diagnostics)
*   Field, Andy. *Discovering Statistics Using IBM SPSS Statistics*. Sage, 2013.
*   Fox, John, and Sanford Weisberg. *Applied Regression Analysis and Generalized Linear Models*. Sage, 2015.

### Machine Learning & Overfitting
*   Hastie, Trevor, Robert Tibshirani, and Jerome Friedman. *The Elements of Statistical Learning*. Springer, 2009.
*   James, Gareth, Daniela Witten, Trevor Hastie, and Robert Tibshirani. *An Introduction to Statistical Learning*. Springer, 2013.

### Python & Data Tools Documentation
*   `yfinance`: `https://pypi.org/project/yfinance/`
*   `pandas`: `https://pandas.pydata.org/`
*   `scikit-learn`: `https://scikit-learn.org/`
*   `statsmodels`: `https://www.statsmodels.org/`
*   `arch`: `https://arch.readthedocs.io/`

### Additional Supporting Sources
*   Brooks, Chris. *Introductory Econometrics for Finance*. Cambridge University Press, 2014.
*   Hamilton, James D. *Time Series Analysis*. Princeton University Press, 1994.

##  Author
Busisani Nyoni-R2418437
