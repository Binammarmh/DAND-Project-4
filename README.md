# DAND-Project-5: wrangling data of WeRateDogs twiiter account.
The project conducted A/B testing of group user conversions between old and new wepage.

# Gathering steps
1. Enhanced Twitter Archive
• Type: CSV.
• Downloaded using: manually from Udacity.
• Content: basic tweet data for all 5000+ of their tweets, but not everything.
2. Image Predictions File
• Type: TSV.
• Downloaded using: programmatically using the Requests library from web link
• Content: images & what stage of dog is present in each tweet according to predictions & confidence level.
3. Tweet Json file
• Type: TXT.
• Downloaded using: tweet IDs in the Twitter archive are queried the Twitter API for each tweet's JSON data
using Tweepy library which are stored in a file called tweet_json.txt
• Read using: reading line by line to get tweet ID, retweet count, and favorite count and stored in csv.
• Content after read: tweet ID, retweet count, and favorite count

# Assessing using two methods : 
• Visual assessment: Done using excel sheets & notes
• Programmatical assessment: Done using different functions such as (info, duplicated, value_counts,etc)

# Cleaning Data using : 
* Define
* Code
* Test.


# Technologies Used
Python, Numpy, Pandas, Matplotlib, StatsModels, Scipy
Jupyter Notebook

