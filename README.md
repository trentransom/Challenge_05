# Two Financial Applications

### Requirements

In order to use this application, you will need to have the following installed on your computer:

- Jupyter Notebook
- Python 3
- The following Python libraries:
    - requests
    - json 
    - pandas 
    - dotenv
    - alpaca_trade_api
    - MCForcastTools

## Emergency Fund Calculator

This Jupyter Notebook application allows users to input information about their portfolio of stocks, bonds, and cryptocurrency in order to determine if they have sufficient funds to create an emergency fund.

### Usage

1. Open the `emergency_fund_calculator.ipynb` file in Jupyter Notebook.
2. Follow the instructions within the notebook to input information about your portfolio.
3. The application will calculate whether or not you have enough funds to create an emergency fund based on the inputted data.

### Notes

- The emergency fund calculation is based on the recommendation that an emergency fund should be equivalent to three months' worth of living expenses.


## Financial Planner

This Jupyter Notebook application allows users to input information about their portfolio of stocks and bonds, and then runs Monte Carlo simulations to determine the optimal weighting of stocks and bonds for their portfolio for their retirement plan.


### Usage

1. Open the `financial_planner.ipynb` file in Jupyter Notebook.
2. Follow the instructions within the notebook to input information about your portfolio of stocks and bonds.
3. The application will run Monte Carlo simulations to determine the optimal weighting of stocks and bonds for your portfolio for your retirement plan.

### Notes

- The optimal weighting determination is based on historical data and is intended to provide a recommendation for asset allocation. It is not a guarantee of future performance.
