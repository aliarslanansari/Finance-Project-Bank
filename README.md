# Finance-Project-Bank
In this data project i am focusing on exploratory data analysis of stock prices. Keep in mind, this project is just meant to practice your visualization and pandas skills, it is not meant to be a robust financial analysis or be taken as financial advice.
We'll focus on bank stocks and see how they progressed throughout the financial crisis all the way to early 2020.

Get the Data

In this section we will learn how to use pandas to directly read data from Google finance using pandas!

First we need to start with the proper imports, which we've already laid out for you here.

Note: You'll need to install pandas-datareader for this to work! Pandas datareader allows you to read stock information directly from the internet Use these links for install guidance (pip install pandas-datareader), or just follow along with the video lecture.


Data

We need to get data using pandas datareader. We will get stock information for the following banks:

    Bank of America
    CitiGroup
    Goldman Sachs
    JPMorgan Chase
    Morgan Stanley
    Wells Fargo

Figure out how to get the stock data from Jan 1st 2016 to Jan 1st 2020 for each of these banks. Set each bank to be a separate dataframe, with the variable name for that bank being its ticker symbol. This will involve a few steps:

    Use datetime to set start and end datetime objects.
    Figure out the ticker symbol for each bank.
    Figure out how to use datareader to grab info on the stock.

Use this documentation page for hints and instructions (it should just be a matter of replacing certain values. Use yahoo finance as a source, for example:

# Bank of America
BAC = data.DataReader("BAC", 'yahoo', start, end)


**WARNING: MAKE SURE TO CHECK THE LINK ABOVE FOR THE LATEST WORKING API. "yahoo" MAY NOT ALWAYS WORK.**
