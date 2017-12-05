# Big Picture Assignment

Your task is to create a page which shows publicly available information about competitors of Apple on the US stock markets. There is starting code already in the repository, but it was created by somebody without a lot knowledge of modern web development methods.

We want to extend this work. In particular, for the companies that are already loaded, we want to know the latest price, the time at which this price was set, and the percentage price change from the previous close. Additionally, we would like to show the logo of the companies in question.

As we want to stay up to date, the price data should automatically update every 30 seconds.

Finally, we want to have a "refresh" button somewhere on the page which, when pressed, immediately refreshes the data. The idea behind this is that we are sometimes very anxious to see price movements. This functionality should work in parallel with the 30 second update time.

The data should be displayed in a table (or table-like structure), like what exists already. The design / layout of the page is not important however, so you don't have to spend effort on that. What counts is the functionality, and what techniques you use to solve the problem.

The IEX has a well-documented API, which should help you greatly:
https://iextrading.com/developer/docs/
