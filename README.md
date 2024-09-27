## Summary: Fast Food Marketing Campaign - A/B Testing

Dataset used: 

A fast-food chain tested three different promotional strategies across various markets to evaluate which promotion leads to the highest sales for a new menu item. Sales were recorded over four weeks for each promotion group. The goal was to determine which promotional strategy has a statistically significant impact on sales.

## Approach

- **Data Overview**: The dataset consists of sales data from 548 stores, with key features such as `MarketSize`, `AgeOfStore`, `Promotion`, and `SalesInThousands`.
- **Exploratory Data Analysis (EDA)**: Distribution of key variables (e.g., MarketSize, Age of Store) was analyzed to ensure comparability between groups.
- **Hypothesis Testing**: Two-sample t-tests were used to compare the performance of the promotions:
  - **Promotion 1 vs. Promotion 2**
  - **Promotion 1 vs. Promotion 3**
- The null hypothesis (no significant difference) was tested at a significance level of α = 0.05.

## Results

![Promotion 1 vs. 2](https://github.com/PolinaBurova/AB-Testing---Fast-Food-Marketing-Campaign/blob/main/1_2_AB%20Test.png)

![Promotion 1 vs. 3](https://github.com/PolinaBurova/AB-Testing---Fast-Food-Marketing-Campaign/blob/main/1_3_AB%20Test.png)

- **Promotion 1 outperformed Promotion 2**: With statistical significance, the average sales for Promotion 1 were significantly higher than for Promotion 2 (58.09 vs. 47.33, p < 0.05).
- **Promotion 1 and Promotion 3**: Although Promotion 1 had higher average sales (58.09 vs. 55.36), the difference was not statistically significant (p > 0.05).

Based on the analysis, the company can confidently implement either Promotion 1 or Promotion 3 for their fast-food retail chain. Between the two, Promotion 1 is the more effective strategy for increasing sales, particularly in medium-sized markets, and should be prioritized to maximize sales performance across stores.


## Suggestions for Improvement

- **Expand Testing Period**: Testing over a longer period might better capture variations in customer behavior.
- **Include More Features**: Incorporating additional features such as customer demographics and product pricing could help in understanding sales drivers.
- **Test for Multiple Hypotheses**: Consider running multiple hypothesis tests (e.g., with other demographic variables) to uncover insights beyond overall sales.

