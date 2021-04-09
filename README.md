# MACD-Crossover-Stock-Scanner-with-Email-Updates
A stock scanner that uses the MACD Crossover method to find potential stocks to buy or sell. It grabs data from Yahoo finance for each stock specified. An email with the list of potential buys/sells is then sent out. For more information about the trading strategy, check out this [link](https://www.dailyfx.com/education/moving-average-convergence-divergence/macd-crossover.html)

### Required Packages:
Most of the packages I used are typical Python Packages, such as Pandas and Numpy, and I'll include the install instructions for the lesser used packages.

```
pip install yfinance
pip install yagmail

```
Yahoo Finance has a limit of 2,000 API calls/hour, so make sure the list has a limit. I'll add a counter and a limit at some point to keep myself from accidently exceeding this limit. 

Yagmail is just another Gmail/SMTP email client, but I really enjoy it's simplicity. It does, however, require the user to have a gmail account. You can use any other email or notification service as desired, but I'll keep using yagmail for now. In later verions I'll add charts and images to the emails, and yagmail appears to make that incredibly easy to do. For more info, here is the [documentation](https://github.com/kootenpv/yagmail#install).

Disclaimer: The information provided is not meant to be taken as financial advice or investing recommendations. It is purely for personal and academic purposes.
