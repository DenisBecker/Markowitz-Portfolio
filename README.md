# Portfolio Analysis
Download Stocks, Build Portfolios and Depict Risk-Return-Diagram

The file **Get_Returns.ipynb** is a Google Colab project. 
Click on the filename. A preview of the file willl open. On the top there is a button/link to open the file in Google Colab.

The file **Portfolio_Cloud.py** generates a cloud of portfolios that are build from stocks. This cloud, together with the stocks and the least-varaince portfolio, will be plotted
a risk-return diagram. The minimum variance is not computed by means of optimization. It is simply the random prortfolio with least variance. In this code we print some intermediate results. Also the calculation of the average deviation is shown in the code.

The file **Portfolio_Cloud_Short_StDev.py** is a short version of **Portfolio_Cloud.py** where all the unnecessary code is removed.

**Portfolio Optimization (Two Assets Only).jpynb:** In this Jupyter Notebook it is illustrated how to find the optimal protfolio (i. e. minimum variance for given return) for two assets only. The SciPy (Scientific Python) package is applied for this purpose. Numerical data is synthetic and not based on real stocks.

**Portfolio Optimization (Given Covariance).jpynb:** In this Jupyter Notebook it is illustrated how to find the optimal protfolio (i. e. minimum variance for given return) for several assets if the covarince matrix is given. The SciPy (Scientific Python) package is applied for this purpose. Numerical data is synthetic and not based on real stocks.
