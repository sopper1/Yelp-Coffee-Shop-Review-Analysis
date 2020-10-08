# ☕ Yelp-Coffee-Shop-Review-Analysis

by Shawn Oppermann

## Introduction

If you could go anywhere in the USA to get coffee, where would you go? This project aims to use Yelp reviews as data to help determine which locations in the county have the best coffee shops. More specifically, the project aims to determine if there is a correlation between coffee shop location in the USA and Yelp rating. I also briefly look at rating correlation with pricing and number of reviews.

## Insights

Unfortunately, there is nothing to suggest any real correlation between location in the USA and Yelp rating. The same goes for both pricing and number of reviews. This may be a result of have very using data points with low ratings, as most ratings ranged from 4.0 to 5.0.

## Tools and Libraries

   * All data in the dataset was gathered via Yelp Fusion, an API that uses the REST standard for querying data.
   * argparse, json, pprint, requests, sys, and urllib are all libraries used to process queries to Yelp Fusion
   * Used library csv to read/write data as a csv file
   * Used libraries matplotlib and pandas to visualize data

## Dataset

    The dataset can be found under the data directory as coffeeshops.csv
    
## References

    Yelp fusion example https://github.com/Yelp/yelp-fusion/blob/master/fusion/python/sample.py
    Yelp Fusion API https://www.yelp.com/fusion
    US State Dictionary https://code.activestate.com/recipes/577305-python-dictionary-of-us-states-and-territories/