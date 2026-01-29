# WiDS-2025, Accio Alpha - Kalman filtering magic

git : https://github.com/throwaway1183/accio-alpha




-> this repository documents my weekly progress in building foundations for data analysis, statistical modeling, and quantitative finance through a combination of theory, coding exercises, and applied projects.

-> overall this repository showcases my progression from statistical foundations to applied modeling techniques, combining probability, regression, time-series analysis, and filtering methods commonly used in quantitative finance, signal processing, and data-driven decision-making.

-> a detailed breakdown of the weeks now follow:




# Week 1
studied the mathematical fundamentals required for data analysis, with a focus on probability theory and random variables including topics such as sample spaces, probability axioms, conditional probability, independance, Bayes theorem, total probability theorem, etc.

learned about discrete and continuous random variables, including probability mass functions (PMF) and probability density functions (PDF). I explored common probability distributions such as Bernoulli, Binomial, Poisson, Normal, Gamma, Beta, and Chi-square, and understood how to compute their mean, variance, and moment generating functions.

covered expectation, variance, covariance, and correlation, along with their properties and applications. Studied joint and conditional distributions and criteria for independence between variables.

practiced numerical computing and data visualization using NumPy and Matplotlib. Performed array creation and manipulation, including indexing, slicing, reshaping, and vectorized operations. Computed statistical measures such as mean, variance, and standard deviation, and applied these operations efficiently using NumPy functions.

this was then followed by an assignment to be solved.


# Week 2
Studied univariate time-series analysis and stationarity testing, with emphasis on the Augmented Dickey–Fuller (ADF) test

Studied linear regression and Ordinary Least Squares (OLS)

Explored multivariate time-series concepts and cointegration for pairs trading strategies


Exercise 1 – Multiple Linear Regression
Analyzed a regression model with interaction terms, interpreted coefficient effects, compared salary outcomes across gender, computed predictions, and evaluated interaction significance.

Exercise 2 – Simple Linear Regression
Implemented OLS regression with mpg vs horsepower, interpreted the model summary, generated predictions with confidence and prediction intervals, plotted the regression line, and assessed model assumptions using diagnostic plots.

Exercise 3 – Stationarity Testing
Plotted the price series, conducted an ADF test on log-prices to assess stationarity, calculated the half-life of mean reversion, and evaluated the feasibility of a mean-reversion trading strategy.

Exercise 4 – Cointegration & Pairs Trading 
Analyzed correlation, estimated a hedge ratio using OLS, constructed the spread portfolio, tested for stationarity with ADF, and computed half-life to determine tradeability.


# Week 3
focused on understanding state estimation and filtering techniques, specifically the Kalman Filter, and how parameter choices affect prediction accuracy and responsiveness in noisy systems.
explored the theoretical foundations of recursive state estimation and studied the provided Week 3 resources to build intuition around process noise, measurement noise, uncertainty propagation, and Kalman gain behavior. Then implemented and experimented with Kalman filtering through coding notebooks and parameter exploration tasks.

Key areas of analysis included:

Measurement noise (R): Increasing R reduced trust in measurements and increased reliance on model predictions, resulting in smoother estimates and smaller Kalman gains.

Process noise (Q): Increasing Q reduced confidence in the prediction model, making the filter more responsive to measurements but producing noisier estimates.

Initial uncertainty (P): Larger P values caused the filter to adapt quickly to measurements, while smaller P delayed convergence due to lower initial Kalman gain.

Incorrect initial state: Verified that the filter can still converge to the true state when process noise is non-zero, demonstrating robustness.


# Week 4

This week consisted of reading various texts on Kalman filtering, essentially serving as a reading assignment