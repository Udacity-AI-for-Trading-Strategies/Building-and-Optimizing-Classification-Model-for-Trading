# Building and Optimizing Classification Model for Trading

## Project Introduction

You are an analyst at a boutique investment firm tasked with coming up with a novel idea for investing in specific sectors of the industry. You've heard that the Utilities, Consumer Staples and Healthcare sectors are relatively resilient to economic shocks and recessions, and that stock market investors tend to flock to these sectors in times of uncertainty. You decide to take the SPDR Healthcase Sector ETF (NYSEARCA: XLV)(opens in a new tab) and try to model its returns' dynamics using a machine learning AI strategy. Your novel idea is to get data for the volatility index (INDEXCBOE: VIX)(opens in a new tab) as a proxy for uncertainty in the market. You also decide to take a look at Google Trends data(opens in a new tab) for the search term "recession" in the United States, in order to try and see if there is any meaningful relationship between the general public's level of concern about a recession happening and the price movements of the Health Care Select Sector SPDR Fund.

You decide to train a binary classification model that merely attempts to predict the direction of XLV's 5-day price movements. In other words, you want to see if on any given day, with the above data in hand, you could reliably predict whether the price of XLV will increase or decrease over the next 5 trading days.