BitlyAPIUsage
=============

Code for basic API Usage of Bitly


1. Hot Phrases

One of the more interesting API endpoints offered by bitly is the hot phrases API. This endpoint returns a list of phrases and related content which is currently receiving a significant amount of clicks.

Query this endpoint to get the current hot phrases and return the top 5 phrases based on click rate. The final values returned should just be the phrases and none of the other data returned by the endpoint.

Below is a sample of what the output should look like (your phrases will be different but format should be the same):

breaking bad
miley cyrus
government shutdown
injury status of starting cornerbacks rashean mathis and chris houston
key questions


2. High Value Links

Another interesting API endpoint that bitly provides is the high value API. Similar to the hot phrases endpoint, the high value endpoint provides bitly links that are receiving a lot of attention right now.

Use the high value endpoint along with other parts of the bitly API to return a list of 10 high value links, along with the number of clicks each link has received in the last day.

Below is a sample of what the output should look like:

http://bit.ly/15clwC2 - 432

http://bit.ly/WT7zYR - 53
http://bit.ly/15BC7mu - 143
http://bit.ly/1eNqttq - 43
http://bit.ly/16qV1yX - 98
http://bit.ly/yGi1de - 483
http://bit.ly/1beexgs - 992
http://bit.ly/1bWh15V - 102
http://bit.ly/1bHafRm - 896
http://bit.ly/162Stn - 423

Again the specific links and counts you return will be different but the format should be the same.
