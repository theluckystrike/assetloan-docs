Amortisation
============

The standard payment formula is

.. code:: text

   P = A * r / (1 - (1 + r) ** -n)

where A is the amount financed, r the monthly rate (APR / 12) and n the
number of monthly payments. Each payment splits into interest (balance * r)
and principal (payment - interest). The balance then drops by the principal.

Worked example: 25,000 at 8.9% for 60 months gives r = 0.0074167 and a
payment of 517.84. Month one interest is 185.42, principal 332.42.

Run the numbers for your own asset at
https://assetloancalculator.com/ .
