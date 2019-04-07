# twitter-wrangling-project

## Overview
This is a wrangling project part of the Udacity Data Analyst Nanodegree. 
The goal of project is to exercise and develop wrangling skills by gathering 
data from multiple sources, assessing data, and cleaning data. I include a 
small report but the majority of the focus of this project is cleaning data.

The data we will be looking it is regarding the twitter profile, WeRateDogs,
which is an account focused on creating tweets about dogs and giving them a
rating out of 10 but always above 10 because "all dogs are good boys".

I will be working with the Twitter API, a text file provided by Udacity, and
a tsv file extracted from a Udacity website using Http requests. I'll then
assess, clean, and present my findings.

## Contents
In this repository there are several files that are used as part of the 
gathering process, produced from cleaning, and are serve as reports.
#### Twitter Credentials
You will need your own twitter credentials to run all the code in 
'wrangle_act'. Store them into a file called 'creds.py' and look at the 
twitter API code block for how to load credentials into the report. 
Otherwise you can skip that and just load the 'tweets_json.txt' file.
#### Code
'wrangle_act.ipynb' - this is the meat of this project. All the gathering,
assessing, and cleaning happens here. Analysis is done using python. 
Libraries used include Pandas, Numpy, Requests, Tweepy, Timeit, etc.
#### Reports
'wrangle_report.html' - walkthrough of my though process when writing
the gathering, asessing, and cleaning code.

'act_report' - with the clean combined dataframe, I draw a couple insights
on the dogs rated via Tweets.
#### Data Files
'twitter_archive_enhanced.tsv' - this file was provided by Udacity and 
has tweet ID information we'll use to access the Twitter API to get more 
individual tweet information.

'image_predictions.tsv' - this file was downloaded from a udacity server
page. The code in `wrangle_act.ipynb` will download this file.

'tweets_json.txt' - json data from Twitter API. Code in `wrangle_act.ipynb`
will also save and write this.

'twitter_archive_master.csv' - the resulting master clean dataframe 
combining all of our data sources into one nice clean data frame.

'dog images' - 'newfoundland.jpg' and 'chihuahua.jpg' are just pictures
of dogs and loaded as part of our report in 'wrangle_act'

