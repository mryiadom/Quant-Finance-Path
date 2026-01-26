# 01-Foundations: Week 1 - Time Value of Money (TVM)

## The Theory
The Time Value of Money is the concept that money available at the present time is worth more than the identical sum in the future due to its potential earning capacity. 

### 1. Future Value (Compounding)
To calculate how much a current investment will be worth in the future, we use:

$$FV = PV \times (1 + r)^n$$

* **PV**: Present Value
* **r**: Periodic interest rate
* **n**: Number of periods

### 2. Present Value (Discounting)
To find the value today of a sum to be received in the future (the "Fair Value"), we rearrange the formula:

$$PV = \frac{FV}{(1 + r)^n}$$

## Implementation
In `week_01_tvm.ipynb`, I implemented these formulas as Python functions to automate the calculation of investment goals and entry costs.
