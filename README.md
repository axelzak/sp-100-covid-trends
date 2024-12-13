# S&P100 covid-trends
Programming in finance project
# Python-Project

We have to find a way to look some words from the Item 2 in 10Q filings of the S&P 100 companies, between 2018 and 2023. Then properly visualize the collected data.

In the code PartA_draft we found a way to download all the stocks from the Edgar database, using YahooFinance we downloaded the S&P100 ticker, name and sector.
We filtered from the Edgar database just the S&P 100 stocks, creating a DataFrame with their CIK, ticker and name. 
This has allowed us to create a list with all the tickers and another list with all the CIK codes, we want to write a code to download all 10Q filings (2018-2023) and search the words "Vaccine" "Pandemic" and "COVID", then count in each quarter how often they were used in each quarter and visualize that data.

Update, 12 december: we have a csv file with all the link to the JSON of these companies, we want to extract the 10Q filings of the period (2018-2023) or count directly from those JSON files the number of times those words were used in their 10Q, a little help on this step would be really appreciated.

WHERE I AM STUCK:
I want to count for each quarter in 2018-2023 how many times the words "vaccine", "COVID" and "pandemic" were used, so I can track these two word trends with some nice data visualizations. If you can help would be really appreciated! Cheers



