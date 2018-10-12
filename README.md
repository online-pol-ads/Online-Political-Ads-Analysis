# NYU's Analysis of Online Political Advertising in United States. 

This report includes our followup analysis of Facebook's political ad archive and our initial analysis of Google and Twitter's archives. We provide analysis of the political advertisers using these online advertising networks and detailed case studies of a few major online political advertisers.

## Introduction

During the summer of 2018, Facebook, Google, and Twitter have all created policies and implemented portals to make transparent and archive U.S. political advertisements that have run on their platforms. The creation of these archives is timely, in light of past misuses of their platforms to manipulate past elections and the upcoming U.S. national elections. Through the lens of these transparency efforts we can begin to understand online political advertising in the United States. The analysis in our report focuses on the time-period from Sept. 9th, 2018 - Sept.22nd, 2018, where we were able to collect fairly complete data for all three platforms. 

Our high level findings are that Beto O’Rourke appears to be the largest political candidate advertiser across all threeplatforms with at least 23.6 million impressions and spending $683,000. However, President Trump is the largest advertiserby total number ads with 9894, with 85% of his ads being smaller “micro-targeted” ads. Our best attempt at a fair comparison shows that Facebook has more advertisers and ads but Google likely has more impressions and spending. This is caused by more “micro-targeted” ads on Facebook’s platform and larger ads on Google’s platform.

Considering spending, when we exclude ads by Facebook and Instagram on their own platform, the advertisers who spentthe most across all three platforms were the Senate Leadership Fund, a right leaning PAC, with $978,000 in total spending, Beto for Texas, with $683,000, and the Congressional Leadership Fund, another right leaning PAC, with $610,000 duringthe study period. 

## Facebook Political Ad Archive Overview

All Facebook and Instagram advertisements that are political or about national issues of public importance as defined by Facebook are now archived for seven years by Facebook. Facebook’s U.S. political ad archive has been available since May 24, 2018 via a web interface to anyone with a Facebook account and includes all ads of a political nature released on or after May 7th, 2018. Facebook has made an API available to some researchers (including us) for programmatic access to this archive. 

## Google Political Ad Archive Overview

In August of 2018, Google also released a political ad archive. Google’s archive dated back to May 31st, 2018 and, similarly to Facebook, Google stated that ads would be retained for 7 years. Google is only including "ads related to elections or issues that feature a federal candidate orofficeholder." The data is released as a BigQuery (SQL-like) dataset, available in its entirety via the Google Cloud service. 

## Twitter Political Ad Archive Overview

In June of 2018, Twitter released their own policy for archiving and making public information related to promoted tweets with political content. The Ad Transparency Center displays data on both political and non-political ads, but displays additional information, including detailed spend and impression information, for political ads. Twitter also publishes relatively detailed impression and spend information for each political ad. There is currently no programmatic way to access the Twitter political ad archive.

## Our Analysis

We investigate the following questions in our report: 
- Which platforms are used the most for political advertising?
- Who are the largest online political advertisers?
- Who are unvetted sponsors? 
- What is the breakdown of political advertising by types of sponsors? 
To answer these we dig into the ad count, spend, and impressions of top advertisers and impressions by advertiser categories and partisan lean across platforms. 

**Overall Datasets**


Platform  |  Total Ads  |  Total Sponsors  |  Total Pages  |  Impressions  |  Spend  |  First Ad Date  |  Last Ad Date
:---:     |   :---:     |   :---:          |   :---:       |  :---:        | :---:   |  :---:          | :---: 
Facebook | 860K | 14087 | 21341 | 5.1B - 14.5B | 89M - 376M | 2014-07-17 | 2018-10-03
Google | 23K | 428 | NA | 677M - 5.8B | 25.7M | 2018-05-31 | 2018-10-01
Twitter | 1151 | 62 | NA | 78M | 1M | 2016-12-21 | 2018-10-02
