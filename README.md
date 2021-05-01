# Stock Market GBM Analysis
Stock Market price prediction by Geometric Brownian Motion.

---
Returns Rn is given by:

![download (4)](https://user-images.githubusercontent.com/63190833/116795231-16b91280-aaf1-11eb-9c9c-3b68d66ae9c2.png)

Pn is price at nth day.

---
Price over time series is given by:

![download (3)](https://user-images.githubusercontent.com/63190833/116795244-3c461c00-aaf1-11eb-8d7e-45fc6e959f15.png)

Starting price is given as Po.

---
***Geometric Brownian Motion:***

GBM is a particular model of the stock market in with the returns are uncorrelated and normally distributed.

---
***Mathematical Translation:***

![download (2)](https://user-images.githubusercontent.com/63190833/116795330-c8f0da00-aaf1-11eb-80f8-f9562358235e.png)

If mean and deviation variables are time dependent, process is *Stationary*.

---
***Mean Variable:***
1. If mean is +ve implies bullish trend.
2. If mean is -ve implies bearish trend.
3. Higher the mean means stronger the trend.

---
***Standard Deviation:***

Deviation is the volatility of the returns.

Higher the deviation variable compared with mean implies more erratic the price.

---
***Portfolio Theory:***

Sharpe ratio with risk-free return equal to 0 is mean/deviation.

---
***Wiener process:***

**Stochastic Differential Equation:**

![download (1)](https://user-images.githubusercontent.com/63190833/116795412-5f250000-aaf2-11eb-8598-a8b5ee7c9050.png)

Wt is the Wiener process(constant).

Solve this equation by using: ***Euler-Maruyama method***

---
***Demerits:***
1. Stock market returns are not normally Distributed.
2. Stock market returns are not normally Stationary.
3. In reality we never have a Continuous Time because transactions are discrete and finite.

---
***Predicting Prices:***

Generate n normally distributed random variables and calculate future prices starting from a start price.

---
***Normal Gaussian Distribution:***

**Probability Density Function is given by::**

![download (5)](https://user-images.githubusercontent.com/63190833/116795594-becfdb00-aaf3-11eb-929e-e120acaed50a.png)

---
By changing the values of variable we can see the change in graph but initially we get this graph of prices:

![Screenshot (133)](https://user-images.githubusercontent.com/63190833/116795489-fc803400-aaf2-11eb-8489-43f262049492.png)


