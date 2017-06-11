# Overview

Calculate profit and loss for trading is tricky. For instance:

- You buy 100 VND at price 10, then buy again 100 VND at price 11.
Now the price is 12, the profit is: 100(12-10) + 100(12-11) = 300.
It's easy to see the cost price is: (100 * 10 + 100 * 11)/200 = 10.5.

- If you buy then sell, what's the cost price then? Does it change?
You buy 100 VND at price 10, then sell 50 at price 11. 
You have 100 VND at cost price 10.
But if you enter and exit position rapidly: (100 * 10 - 50 * 11)/150 = 3.
Strange, right?

- If you buy 100 VND @10, buy 100 VND @9, then sell of 100 VND @11.
How do we know if 100 VND of the sell order matches with @10 or @9 deal?
Or it should realize with the cost price of the moment of the sell order?

