# project-one
In Finance

For our group project, we analyzed two dividend-yielding stocks to see if they fair better than an index fund that follows the NASDAQ. We compared two distinct firms from the real estate industry: PennyMac Mortgage Investment Trust, and Realty Income Corp. These two companies yield dividends and have different trends as publicly traded companies.

In order to successfully perform our analyses, we first had to find and import the various appropriate csv's from the nasdaq database, and also Kaggle. For the individual stock data frames, we successfully completed this task by installing the nasdaq library as a dependency an ran a command to pull that appropriate information, allowing us to then write out as a csv and push to our main branch on GitHub. For the NASDAQ values, we relied on Kaggle and formatted the file to correspond to the same date format as our other data frames. To make the data frames easier to work with, we also reset the index to the dates that correspond with our data, making it much faster and simpler to plot our visualizations.

We ran into a small problem with our data while using these data frames: we came across a set of data that was missing a single line of values, rendering us unable to use multiple data frames for plotting and correlations. So, before really analyzing our data as a team, we had to pull our ticker information from an open-source virtual environment that was created by Stefanie Molin and licensed by MIT. This virtual environment allowed to quickly and seamlessly import a unified collection of data frames, as well as let us add a market index fund VTI to compare our stocks' performances.

Using an index fund for comparing our stocks to the overall growth of the stock market was essential for plotting our comparisons to scale in a way that wouldn't be obscure. In other words, because the values of the NASDAQ were so large, there was no feasible way to plot its data with either of our picked stocks simultaneously.

With the data we collected we were able to answer meaningful and important questions about the stocks we picked in our project. As our data from the cumulative analysis shows, the 'single dollar' investment model for each of our three stock options shows that the index fund VTI distinctly outperforms our individual stocks.

We were also able to show the correlation between each stock and the NASDAQ itself. While PMT had a very strong correlation to the overall market, Realty Investment Corp did not, and in fact had a negative correlation, signifying that the stock is either on a downward overall trend, or that its business is not heavily affected by the stock market.

When comparing the overall trend of each investment pick, we can see (in question #4, 'how do these stocks compare to an index fund?') that the index fund VTI performed resoundly better than either of the two individual stocks. This, of course, shows that while picking individual stocks can be lucrative if you're lucky, it's usually easiest and safest to invest in the aggregate market. 

Lastly, we measured the volatility of both real estate stocks to further inform us of the inherent risks involved with picking individual stocks. For this metric, we calculated the standard deviation of each stock's closing price for every trading day in our datasets. The graphed many swings of change, signifying an inherent risk for picking either of these stocks at any point in time. 

Here is the link to our google slides presentation: https://docs.google.com/presentation/d/15rNr_Ld3Z-x6Hex481TG3wLFMnqRjrASgSxzzzyGqpc/edit?usp=sharing
