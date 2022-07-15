# Financial Planning Tools

# About
I’ve decided to start a fintech consulting firm that focuses on projects to benefit local communities. I just won my first contract with a large credit union. The project entails building a tool to help credit union members evaluate their financial health. Specifically, the credit union board wants the members to be able to do two things. First, they should be able to assess their monthly budgets. Second, they should be able to forecast a reasonably effective retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds. The chief technology officer (CTO) of the credit union wants me to develop a prototype application to present at its next assembly.

# What I Created
I created two financial analysis tools by using a single Jupyter notebook:

1. A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

2. A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.
