# The Unbearable Weight of Sentiment Analysis

## Description

This quick and short project aims to analyze the sentiment of tweets related to Novak Djokovic, a professional tennis player. The sentiment analysis is performed using the VADER (Valence Aware Dictionary and sEntiment Reasoner) package in Python.
For this task tweets were scraped using the snscrape package, and there were scraped only tweets related to Novak Djokovic between 01-2019 and 03-2023.
Only official tweets from the most famous Twitter accounts about tennis were downloaded.

List of accounts: ['Tennis', 'ITFTennis', 'TennisChannel', 'Wimbledon', 'usta', 'TennisAustralia', 'TennisTV', 'DavisCup', 'FedCup', 'rolandgarros', 'usopen', 'AustralianOpen']

Below is overall sentiment about Djokovic.

<img src="/graphs/overallSentiment.png" alt="Overall Sentiment" width="500" height="300">

Even though those accounts are official ones, and they usually have a neutral or positive tone in their posts, we could notice some spikes in negative sentiment around specific dates.
For example, in June 2020 (20-06) Djokovic got coronavirus and also organized an Adria tour in the Balkan region. Those two things gave him a spike in negative sentiment in those 4 years. 
Also, there was a spike in negative sentiment in September 2020 (20-09) when he was disqualified from the US Open. 
Below is a graph showing percentages of sentiments per month.

<img src="/graphs/percentage.png" alt="perc" width="800" height="500">

In the end, if we look at the graph below, it is an overly positive sentiment, where we notice spikes in the number of tweets around major tournaments.
The graph shows counts of sentiments per month.

<img src="/graphs/count.png" alt="perc" width="800" height="500" style="background-color:white">
