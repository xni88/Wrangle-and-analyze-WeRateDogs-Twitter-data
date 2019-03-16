# Wrangle-and-analyze-WeRateDogs-Twitter-data

WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. Using python and its libraries, I gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it.

1. Gather data

twitter_archive_enhance.csv is given by Udacity. Additional data including tweet's retweet count and favorite count are obtained by querying the Twitter API for each tweet's JSON data using Python's Tweepy library. Each tweet's entire set of JSON data is saved in a file called tweet_json.txt. All the data are gathered in a jupyter notebook called wrangle_act.ipynb.

2. Assess data

Assess the gathered data visually and programmatically for quality and tidiness issues. At least eight quality issues and two tidiness issues should be assessed.

3. Clean data

Clean each of the issue that is documented while assessing. The whole process is performed in wrangle_act.ipynb.

4. Store, analyze and visualize the wrangled data

The cleaned dataframe is stored in a cvs file with the main one named as twitter_archive_mater.csv. Analyze and visualize data in jupyter notebook wrangle_act.ipynb.

5. Report on summary of data analyses and visualization

Communicate the insights and display the visualizations produced from the wrangled data.
