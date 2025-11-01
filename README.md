# How should you allocate limited space in a warehouse?
We're running a business which sells items out of a warehouse. We only get stocked periodically, and thus if we run out of an item in between stockings, we might lose revenue. We thus need to calculate an optimal allocation of products in our warehouse. We need to consider the profitability, and demand probability distribution, to make tradeoffs between profitable items, bestselling items, etc.

Here we use some basic assumptions to optimise allocations given basic information about products.
Assumptions:
1. We don't care about excess NWC.
2. There are no carrying costs/variable costs of warehouse stocking etc.
3. Demand for items is normally distributed with a known mean and standard deviation (can be easily modified for other distributions)

*see demo.ipynb for an example of how the module can be used, mymodule.py contains the code behind it*
