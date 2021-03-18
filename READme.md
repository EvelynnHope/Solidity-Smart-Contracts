build smart contracts to automate some company finances to make everyone's lives easier, increase transparency, and to make accounting and auditing practically automatic!
 
This is why we program smart contracts with Solidity by creating 3 ProfitSplitter contracts. These contracts will do several things:

*Pay your Associate-level employees quickly and easily.*

*Distribute profits to different tiers of employees.*

*Distribute company shares for employees in a "deferred equity incentive plan" automatically.*



## Associate Profit Splitter contract 

This will accept Ether into the contract and divide the Ether evenly among the associate level employees. This will allow the Human Resources department to pay employees quickly and efficiently.

![Deploying AssociateProfitSplitter](./AssociateProfitSplitter.GIF)

## Tiered Profit Splitter 

This contract distributes different percentages of incoming Ether to employees at different tiers/levels. For example, the CEO gets paid 60%, CTO 25%, and Bob gets 15%.

![Deploying TierdProfitSplitter](./TieredProfit.GIF)

## Deferred Equity Plan 

This contract models traditional company stock plans. This contract will automatically manage 1000 shares with an annual distribution of 250 over 4 years for a single employee.

![Deploying DeferredEquityPlan](./EditedDefferedEquity.GIF)