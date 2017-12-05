# Big Picture Assignment

Your task is to create a page which shows publicly available information about competitors of Apple on the US stock market.

**This task should take about 2-3 hours.**

You are encouraged to use a reactive framework, such as AngularJS or ReactJS.

The data is pulled from the IEX, which has a well-documented API:
https://iextrading.com/developer/docs/

## The task requirements

There is code already in the repository to get you started, but it was created by somebody without a lot knowledge of modern web development methods. We want to extend and improve this work. In particular we want to show for each company
* the latest price
* the time at which this price was set
* the percentage price change from the previous close
* a picture of the company logo

As we want to stay up to date, the price data should automatically update every 30 seconds. You should show somewhere on the page when your last update was done.

Finally, we want to have a "refresh" button somewhere on the page which, when pressed, immediately refreshes the data. The idea behind this is that we are sometimes very anxious to see price movements. This functionality should work in parallel with the 30 second update time.

The data should be displayed in a table (or table-like structure), like what exists already. The design / layout of the page is not very important, so you don't have to spend a lot of effort on that. What counts is the functionality, and what techniques you use to solve the problem.
