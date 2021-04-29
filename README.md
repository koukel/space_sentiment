![alt text](https://github.com/koukel/space_sentiment/blob/main/banner.png)

# Public Sentiment of Commercial Versus Government Space Entities

## Project Overview

This research project was the capstone for the Master of Science in Data Analytics from Western Governors University.

This study will use messages written by the public on the social media network Twitter, or “tweets”, to gauge the public sentiment towards entities in the space industry to answer the question “Is there a significant difference in the sentiment expressed in tweets involving commercial entities compared to government agencies involved space exploration?”

To accomplish this analysis, data was collected from Twitter for the companies SpaceX, Blue Origin, and Virgin Atlantic, and the National Aeronautics and Space Administration (NASA), the European Space Agency (ESA), and the Jet Propulsion Laboratory (JPL) government organizations.  Collected data raged over two years beginning in April 2019 through March 2021.  The tool used to gather data was [snscrape](https://github.com/JustAnotherArchivist/snscrape).

The gathered data was cleaned to remove duplicate messages, unusual characters, and any links or mentions (ex. “@NASA”).   Additionally, any tweets from the organizations being studied in this research were removed to eliminate bias.  Sentiment analysis was performed to calculate a score for the expressed polarity, and that score was used to apply labels of positive, negative, and neutral to each tweet.

Bar charts were created to explore the overall expressed sentiment, sentiment by sector, and additionally the sentiment towards each individual entity.  The sentiment over time was also visualized.  A Chi-square test was then performed, which compares two categorical variables to determine if the distributions vary from each other (Glen, 2020).  The test statistic is calculated using the observed and expected values from a frequency table.  This statistic is a single value that describes the amount of difference between the observed frequency and the frequency that is expected if there were no relationship.  The test statistic can be used to calculate a p-value to determine the significance of the relationship between the variables.

## Necessary Software

To run the .ipynb file, the following software and packages will need to be installed:

* [Python 3 (link provided via Anaconda install)](https://www.anaconda.com/products/individual)
* [Jupyter Notebook](https://jupyter.org/install)
* [Pandas](https://pandas.pydata.org/docs/getting_started/install.html)
* [Numpy](https://numpy.org/install/)
* [Matplotlib](https://matplotlib.org/3.1.1/users/installing.html)
* [Seaborn](https://seaborn.pydata.org/installing.html)
* [snscrape](https://github.com/JustAnotherArchivist/snscrape)
* [WordCloud](https://anaconda.org/conda-forge/wordcloud)
* [Pillow](https://anaconda.org/anaconda/pillow)
* [TextBlob](https://anaconda.org/conda-forge/textblob)
* [Scipy](https://anaconda.org/anaconda/scipy)
