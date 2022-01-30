# risk_return_analysis
A quantitative analysis of four fund portfolios. Uses key risk-management metrics to recommend the fund with the most investment potential. This project contains data preparation, an analysis, and visualizations for key risk and return metrics. The quantitative analysis will cover the performance, volatility, risk, risk-return profile, and portfolio diversification.

---

## Technologies

This project uses the following libraries and dependencies:
+ **Anaconda**: an open source package and environment management system.
+ **JupyterLab**: an extensive environment using web-based user interface designed for data analysis. 
+ **Pandas**: (included in Anaconda) a Python package data analysis toolkit.
+ **Pathlib**: imports modules.
+ **matplotlib inline**: library to create static, animated, and interactive visualizations in JupyterLab.
+ **NumPy**: library that provides a multidimensional array objects and used for scientific computing and data science. 

---

## Installation Guide

Check to ensure that Jupyterlab is installed on your machine by entering the following into your environment:
```
pip install jupyterlab
pip install numpy
```
To launch JupyterLab:
  1. Open terminal window, and type ```conda activate dev```.
  2. Type ```jupyter lab```. JupyterLab user interface should open in your browser. 
      a. Or copy and paste one of the URLs: "http://localhost:8888/lab?token=..." into web browser. 

To exit JupyterLab:
  1. On your web browser, use the Run button to shut down any running kernel sessions.
  2. On the menu bar, on the File menu, select Shut Down. 
  3. Okay to close tabs once a dialog box with "Server stopped" message indicates the server has stopped. 
  4. Navigate to terminal window, where you launched JupyterLab and type ```conda deactivate```. This will return you to your ```base``` environment. 

---

## Usage 
Using the technologies to import CSV files, create dataframes, and clean up data:
![image](https://user-images.githubusercontent.com/96001018/151694326-5672e1b9-16cc-4b67-89d3-18393b45376e.png)

**Analyze the Performance**: Analyze the data to determine if any of the portfolios outperform the broader stock market (S&P 500). Calculate and create a visulatization of the cumulative return values for the four funds and the S&P 500 over time.  
![image](https://user-images.githubusercontent.com/96001018/151694669-d30e6123-d05f-4d11-8863-fa47cc7fc708.png)

**Analyze the Volatility** of each of the fund fund portfolios and of the S&P 500 Index by using box plots. 
![image](https://user-images.githubusercontent.com/96001018/151694657-4af2221e-95a4-4bc1-99c9-1b6045826562.png)

**Analyze the Risk** of each portfolio by using standard deviation and the beta. 
![image](https://user-images.githubusercontent.com/96001018/151694578-d2598fef-ac1f-4461-9f11-2a21fd739d2c.png)

**Analyze the Risk-Return Profile** Using the Sharpe Ratios for each portfolio to determine the overall risk of the portfolio. 
![image](https://user-images.githubusercontent.com/96001018/151694616-b340dbf6-20d0-42a1-8791-d1478c5fd14c.png)

**Diversify the Portfolio** Evaluate how the portfolios react relative to the S&P 500. Recommendation included at the end of the analysis. 

---

## Contributors

Leigh Anne Badua leighbadua@gmail.com 

---

## License

+ [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/)
