# Financial Planner Report

* Prepared By Dan Smith
* 05-API
_____________________

![Financial Planner](/Images/fin-planner.png#center)

_____________________
### Budget Analysis
 
#### Accounts Summary and Balances
* Plaid Gold Standard 0% Interest Checking: $110
* Plaid Silver Standard 0.1% Interest Saving: $210
* Plaid Bronze Standard 0.2% Interest CD: $1000
* Plaid Diamond 12.5% APR Interest Credit Card: $410
* Plaid Platinum Standard 1.85% Interest Money Market: $43200
* Plaid IRA: $320.76
* Plaid 401k: $23631.98

#### Income
* Last Years Before Tax Income: $7,893
* Current Monthly Income: $500
* Projected Before Tax Yearly Income: $7,389

#### Expenses

##### Transaction Categories (last 90 days):
   ![Budget Categories](/Images/budget_categories.png#center)

##### Sample Transactions
   ![Sample Transactions](/Images/sample_transactions.png#center)

##### Expenses Per category
   ![Spending Categories](/Images/spend_per_category.png#center)

##### Expenses Per Month
   ![Monthly Spending](/Images/spend_per_month.png#center)




#### Summary and Recommendations

At present, expenses far outpace income.  We recommend to first seek additional income as current and recent past income levels are well below the US Dept of Health and Human Services "Poverty Guidelines of 2020" for a single person/family income. (*[Reference](https://aspe.hhs.gov/poverty-guidelines)*)  Secondly, reducing expenses where possible will help balance expenses vs current income.

______________
### Retirement Planning

#### Portfolio Allocation
* 60% Stocks (SPY)
* 40% Bonds (AGG)

##### Sample Daily ROI
   ![Sample Daily ROI](/Images/sample_daily_roi.png#center)

##### Monty Carlo Simulations
   ![500 Monte Carlo Simulations](/Images/500_monte_30year.png#center)


##### Probability Distribution: Cumulative Returns 
   ![Return Distributions](/Images/probability_plot_confidence90.png#center)

#### Retirement Analysis
* Expected cumulative returns at 30 years, 10th percentile: 119.02x
* Expected cumulative returns at 30 years, 50th percentile: 199.08x
* Expected cumulative returns at 30 years, 90th percentile: 320.56x

Given an **initial $20,000** investment:
* expected return at 10th percentile: $2,380,549.70
* expected return at 50th percentile: $3,981,677.14
* expected return at 90th percentile: $6,411,230.97

Given the current annual income and Based on 10th percentile return of $2,380,549.70, a 4% retirement withdrawl ($95,221.99) would far exceed the current projected annual income ($6,085).

**50% Increase:** Updating the initial investment from **$20,000 to $30,000** increases the 4% retirement income from $95,221.99 to $142,832.98.
This is an additional $47,610.99.

#### Optional Scenario Analysis
##### Sample Cumulative Returns at 5%, 50%, an 95% quartiles
   ![Return Distributions](/Images/sample5_50_95_quartiles.png#center)

##### Plot of Returns at 5%, 50%, an 95% quartiles  
   ![Return Distributions](/Images/plot_cumulative5_50_95_quartiles.png#center)

##### Plot of Returns in USD   
   ![Return Distributions](/Images/plot_portfolio_cumulative5_50_95_quartiles.png#center)

