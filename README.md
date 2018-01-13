# Using Network Analysis in the Era of Fake News

This project is motivated around using Twitter as a tool to analyze how Twitter
users (both regular and 'Verified', from the USA) have reacted to Donald Trump's
denigration of the Mainstream Media as "Fake News".

## Tentative Gameplan

1) Write code which gets a random set of Tweeters, and analyze their past tweets
(/ scrapes all verified Tweeters)
OR Alternatively get a random set of tweets with buzzwords for each time period

2) See what information we can glean from said Tweeters, and their social networks
(ie we could predict political affiliation, gender, tag interests, try to
 get demographic information)

3) Scan said tweets for data measures of interest, relating to the project
(ie sentiment analysis on 'The New York Times', 'Washington Post', 'CNN',
'Fake News', 'Donald Trump').

4) Try to statically visualize the data using Gephi or something like that.

5) See how opinion changes over time, over various demographic groups, perhaps
with some real time visualization using d3.js and a local server. Write some
nice visualization code for interactive charts.

**Links that I have deemed helpful for this project:**

[1] https://stackoverflow.com/questions/2211853/whats-a-good-way-to-select-a-random-set-of-twitterers
[2] http://cnets.indiana.edu/wp-content/uploads/conover_prediction_socialcom_pdfexpress_ok_version.pdf
[3] https://www.youtube.com/watch?v=lPr60pexvEM
[4] https://github.com/taspinar/twitterscraper
[5] https://github.com/taspinar/twitterscraper/issues/46 (geofiltering of Twitter users)

Attributions:

I use twitterscraper to scrape tweets; ergo, the code within the `twitterscraper` is not mine, and is instead from [INSERT REPO LINK].
