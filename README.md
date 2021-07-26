# Option Stratergies
This code has two parts:
- Hedging a futures position.
- Implementing a Delta Neutral Short-Strangle.

All historic data used in the implementations is present in the `Data` folder.


## Requirements
- [yfinance](https://pypi.org/project/yfinance/) : Access data from Yahoo Finance.
- [py_vollib](http://vollib.org/documentation/python/1.0.2/) : Provides various functions with respect to the Black-Scholes-Merton model.
- [Pandas](https://pypi.org/project/pandas/)
- [NumPy](https://pypi.org/project/numpy/)
- [Matplotlib](https://pypi.org/project/matplotlib/)
- [SciPy](https://pypi.org/project/scipy/)

## Results
- Futures position was hedged and losses were successfully reduced.
<img width="304" alt="Capture1" src="https://user-images.githubusercontent.com/62967830/127073252-e0268f04-fc44-4c5b-abd2-24055fc33153.PNG">

- Delta Neutral Short-Strangle returned the following profit.
<img width="303" alt="Capture2" src="https://user-images.githubusercontent.com/62967830/127073270-ac6d42d7-7aa1-4095-8fe2-7405511433e4.PNG">
