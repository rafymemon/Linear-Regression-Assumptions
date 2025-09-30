# Linear Regression Assumptions

When applying **Linear Regression**, it’s important to check whether certain assumptions hold true. Violating these can lead to biased, inefficient, or misleading results.

##  Assumptions

1. **Linearity (No Non-Linearity)**

   * The relationship between independent variables and the dependent variable should be linear.
   * Non-linear patterns may require transformations or non-linear models.

2. **No Multicollinearity**

   * Independent variables should not be highly correlated with each other.
   * High multicollinearity inflates variance and makes it hard to interpret coefficients.

3. **Normality of Residuals**

   * The residuals (errors) should be approximately normally distributed.
   * This is crucial for valid hypothesis testing and confidence intervals.

4. **Homoscedasticity**

   * The variance of residuals should remain constant across all levels of the independent variables.
   * Heteroscedasticity (unequal variance) can lead to inefficient estimates.

5. **No Autocorrelation of Errors**

   * Residuals should be independent of each other.
   * Autocorrelation (common in time series data) violates independence and biases inference.

---

Checking these assumptions ensures that the results from a linear regression model are reliable and interpretable. If assumptions are violated, consider transformations, feature engineering, or switching to alternative models.
