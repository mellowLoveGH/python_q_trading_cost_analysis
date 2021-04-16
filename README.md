# python_q_trading_cost_analysis
python, q, Calculate the trading cost analysis, VWAP - volume weighted average price, algorithmic trading

Tick data (trade and quote) is provided in the month of 2020 Dec (trade.csv and quote.csv)

use those tick data to calculate the trading cost.

Transaction Cost Analysis (TCA) format includes 3 parts:
1) Order Characteristics.
• Notional: (million) the whole sum of size/volume * price
• ADV%: order size as percentage of average daily volume (or volume in that day)
• Spread in bps (bid ask spread during order execution)
• Trading speed(executed order quantity / market volume during order execution)
2) Cost, Key Trading Benchmark.
• Arrival:
• iVWAP:
• Open/Close
• PWP20
General Cost Equation: Cost = 10000 ∗ side ∗ (𝐵𝑒𝑛𝑐ℎ𝑚𝑎𝑟𝑘 − 𝐹𝑖𝑙𝑙𝑒𝑑𝑃𝑟𝑖𝑐𝑒)/𝐵𝑒𝑛𝑐ℎ𝑚𝑎𝑟𝑘
3) Fill Statistics
• MOO/MOC%: How much percentage of the order is done by at Market On Open / Market On Close
• Passive/Aggressive %: How much of the order is done passively or aggressively

The first Q language file is just a example to work through how to do it.
While the python code is the real answer/solution.

For python code, 
1) review5530_01.ipynb, it is the whole practices for this course, and the last part is the codes for this project, but not full.
It is a good template for you to learn Algorithmic trading, if you are interested in this subject/course.
2) assignment2_5530.ipynb, it is the clear code for this project, run it will show the result as the screenshot.
