# Fake News Survey Data and Analysis

This repository contains data, analytic code, and findings based on a large-scale survey conducted by Ipsos Public Affairs for BuzzFeed News.

The findings support the BuzzFeed News article, "[Most Americans Who See Fake News Believe It, New Survey Says](https://www.buzzfeed.com/craigsilverman/fake-news-survey)," published December 6, 2016. That article also contains additional details about the survey design and context.

## Data

- General cross-tabs, compiled by Ipsos, and a data dictionary describing the variables, can be [found here](docs/).

- The raw survey response data, courtesy of Ipsos, can be [found here](data/), as both CSV and SPSS files.

- BuzzFeed News has also created a [simplified CSV](data/headline-responses.csv) containing the following main columns for each headline presented to each respondent:
    - Respondent ID
    - Headline ID (A-K)
    - Whether this headline is one of the five fake-news headlines
    - Order in which the respondent saw the headline (1-6)
    - Whether the respondent recalled having seen or heard about the headline (`yes`/`no`/`unsure`)
    - Whether the respondent believed the headline to be accurate (`very accurate`/`somewhat accurate`/`not very accurate`/`not at all accurate`)
    - The respondent's survey weight, as determined by Ipsos

## Analysis

A notebook containing the calculations can be [found here](notebooks/survey-analysis.ipynb). It's written in Python, but the resulting tables should still be generally legible to non-prgrammers.

## Feedback / Questions?

Contact Jeremy Singer-Vine at jeremy.singer-vine@buzzfeed.com.

Looking for more from BuzzFeed News? [Click here for a list of our open-sourced projects, data, and code](https://github.com/BuzzFeedNews/everything).
