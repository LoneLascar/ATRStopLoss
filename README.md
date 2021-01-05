# ATRStopLoss
This program will return the stop loss for a given Equity, Forex or Cryptocurrency pair.
Using the ATR calculation, you are able to determine where your stop loss should be, based on the enough data to reflect the asset. You can also determine whether your position is currently profit or loss.

Data is very important in algorithmic trading and trading in general, which is why I am thankful for Alpha Vantage's service and Crypto Watch for providing a user-friendly API.
The main features I learnt from programming ATRStopLoss was to do with Classes and API's. This was a really fun project and challenging, it's very important when retrieving data and
analysing the dataset, that you have enough in order to make the best judgement. Which is exactly what ATR requires to better represent the particular asset.

Interesting Features:
I chose to cache the results into a json file, this allowed for faster data retrieval times.

I also chose to employ threading, one thread for storing the data (json file), which allowed for a smoother process time for calculating the ATR.

If a dataset is too old, the data will be removed or replaced with a new dataset that better reflects the assets price at that particular time.

The UNSW Forex Society describes this concept here (which inspired this project):

[Video](https://www.youtube.com/watch?v=2PFzdoEyq0Y)