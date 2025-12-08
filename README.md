# Introduction
* The company has developed a new web page in order e-commerce website to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product.
* Our goal is to work A/B test run through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

# Hypothesis Formula
## Business Hypothesis
- $H_0$ : The new page's conversion rate is the same as the old page
- $H_1$ : The new page's conversion rate is different than the old page

## Statistical Hypothesis
- $H_0 : p = p_0$
- $H_1 : p \not= p_0$

A confidence level of 95% (α = 0.05) and a conversion rate of 2%.

# Dataset
The data used in this project is [E-commerce A/B Testing](https://www.kaggle.com/datasets/ahmedmohameddawoud/ecommerce-ab-testing) data from the Kaggle platform.

# A/B Testing Phase
- Exploratory Data Analysis
- Data Cleaning
- Data Visualization
- Hypothesis Testing
- Conclusion

# Conclusions

From the A/B testing, we can conclude:
1. The p-value from the test result  is 0.19 which is above our threshold of α = 0.05.
2. The statistical conclusion would be that we failed to reject the null hypothesis.
3. We don't have enough statistical evidence to conclude that the new page resulted in better / worse conversion rate for our platform.
4. With this result, we can safely say that we should not implement the new design at the moment.
