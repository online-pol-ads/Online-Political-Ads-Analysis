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
</br>
To answer these we dig into the ad count, spend, and impressions of top advertisers and impressions by advertiser categories and partisan lean across platforms. 


**Overall Datasets**


Platform  |  Total Ads  |  Total Sponsors  |  Total Pages  |  Impressions  |  Spend  |  First Ad Date  |  Last Ad Date
:---:     |   :---:     |   :---:          |   :---:       |  :---:        | :---:   |  :---:          | :---: 
Facebook | 860K | 14087 | 21341 | 5.1B - 14.5B | 89M - 376M | 2014-07-17 | 2018-10-03
Google | 23K | 428 | NA | 677M - 5.8B | 25.7M | 2018-05-31 | 2018-10-01
Twitter | 1151 | 62 | NA | 78M | 1M | 2016-12-21 | 2018-10-02

**Federal Candidates Only Results (Sept. 9th, 2018 - Sept. 22nd, 2018)**

Results | Facebook | Google | Twitter
:---:   | :---:    | :---:  | :---:
Total Advertisers | 281 | 172 | 24
Total Ads | 18.5K | 3.5K | 103
Total Impressions | 76M - 220M | 114.5M - 1.2B | 5.8M
Total USD Spend | 1.1M - 4.8M | 6.3M | 86K
Average Impressions Per Ad | 9K - 25K | 33K - 340K | 56K
Average USD Spend Per Ad | 153 - 685 | 1.8K | 265
Cost Per Impressions | 0.006 - 0.072 | 0.055 - 0.005 | 0.015

**Top Advertisers by Ad Count**

Facebook | Total Ads | Google | Total Ads | Twitter | Total Ads
:---     | :---:     | :---   | :---:     | :---    | :---:
The Democratic National Committee | 7263 | NextGen Climate Action Committee | 363 | Beto O’Rourke | 24 
Home Financial Helper No Cost Solar Program | 7202 | Priorities USA Action & House Majority PAC | 274 | Senate Democrats | 17
Donald J. Trump for President, Inc. | 5264 | With Honor Fund, Inc. | 204 | David E. Price | 12
The  Trump  Make  America Great Again Committee | 4616 | Senate Leadership Fund | 197 | Senate Leadership Fund | 10
Solar Programs In CA Counties | 4072 | CFG Action Montana | 149 | Adam Schiff | 8
Michigan Planned Parenthood Votes Super PAC | 3790 | Heritage Action For America | 137 | Ted Cruz | 5
The ACLU | 1897 | Gale Partners LLC | 132 | John K. Delaney | 3
NextGen Climate Action Committee | 1252 | Josh Hawley for Senate | 93 | Steve Ferrara | 3
Concealed Online| 1181 | Heller For Senate  | 85 | Millionaire Claire | 2
Kamala Harris for Senate | 1151 | Mike Gallagher For Wisconsin | 80 | Doug Ducey for Governor | 2


**Top Advertisers by Spend**

Facebook | Min Spend | Google | Total Spend | Twitter | Total Spend 
:---     | :---:     | :---   | :---:       | :---    | :---:
Facebook | 802K | Senate Leadership Fund | 890K | Beto O’Rourke | 58K
Instagram | 650K | Congressional Leadership Fund | 580K | Kirsten Gillibrand | 9K 
Beto for Texas | 411K | Americans For Prosperity | 394K | Senate Leadership Fund | 7K
News For Democracy | 394K | Priorities USA Action & House Majority PAC | 291K | Millionaire Claire | 5K
the NRCC | 272K | NRSC | 269K | Senate Democrats | 2.4K
Priorities USA Action and SMP | 242K | Beto For Texas | 214K | Suggested Politics | 2K
National Education Association | 131K | American Conservative Union | 201K | Randy Bryce | 1K
the Coalition to Defeat Question | 3127K | NextGen Climate Action Committee | 177K | Yes on A Strengthen the Seawall | 298
MO Research, Inc. | 114K | Texans Are | 175K | Peter Roskam | 212
NextGen Climate Action Committee | 111 | KNRCC | 174K | Adam Schiff | 146


**Top Advertiser by Impressions**

Facebook | Min Impressions | Google | Min Impressions | Twitter | Impressions
:---     | :---:           | :---   | :---:           | :---    | :---:
Beto for Texas | 19.8M | Senate Leadership Fund | 26M | Beto O’Rourke | 3.7M
News For Democracy | 16.4M | Heritage Action For America | 11.4M | Kirsten Gillibrand | 649K
Priorities USA Action and SMP | 14.5M | Priorities USA Action & House Majority PAC | 8.4M | Senate Leadership Fund | 558K
the NRCC | 12.5M | Priorities USA Action & SMP | 7.4M | Millionaire Claire | 423K 
Comedy Central | 12.3M | NextGen Climate Action Committee | 6.6M | Senate Democrats | 196K
State Run Films | 10M | NRSC | 5M | Suggested Politics | 126K | MO Research, Inc. | 9.3M | No Labels Action, Inc. | 3.1M
Randy Bryce | 83K | NextGen Climate Action Committee | 8.9M | Public Advocate of the United States | 3M 
Yes on A Strengthen the Seawall | 22K | the Coalition to Defeat Question | 37.5M | NRCC | 2.7M
Joan Greene | 22K | Need to Impeach | 6.2M | Congressional Leadership Fund | 2.5M | Peter Roskam | 10K


**Facebook Unvetted Sponsor Results**

Unvetted Sponsors | 
:---:             | :---:
Total Ads | 2K
Total Spend | 1.6M
Total Impressions | 8.5M 

## Case Studies 
We present a deep dive review of the online political advertising of two candidates, Beto O'Rourke and President Trump. We only present an excerpt on the web page, please refer to the report for the complete case study. 

### Beto O'Rourke
Beto O’Rourke is one of the few advertisers who is actively paying for ads on all three platforms. He is a Democratic candidate for Senate in Texas. During the time period of our study, September 9th - September 22nd, O’Rourke had 44 ads on Google properties with impressions, and spent $213,500. 20 of those ads had fewer than 10,000 impressions, 13 had between 10,000 and 100,000 impressions, ten had 100,000 - 1 million impressions, and one had between one million and ten million impressions. All these ads are AdWords text ads soliciting donations through ActBlue.com, a fundraising portal widely used by Democraticcandidates. He spent $58,265 on these tweets for a total of 3,756,650 impressions. On Facebook, the Beto O’Rourke page had 520 ads, with a total spend of $411,300 for a minimum of just under 20 million impressions. All these ads were paid for by "Beto for Texas", his campaign. Across the three platforms during the time period, Beto O’Rourke spent $683,000 for a total of at least 23.6 million impressions.

### President Donald J. Trump
President Trump is by far the most prolific political advertiser on Facebook in terms of number of ads. During the study period, we were able to find 9,880 ads linked to his official Facebook page, but because of the rate limits Facebook imposed on our data collection, it is likely there were many ads we were not able to retrieve. Ads on this page are paid for by two different sponsors. Of the 9,880, 5,264 were paid for by "Donald J. Trump for President, Inc.", his campaign, and 4,616 were paid for by "theTrump Make America Great Again Committee". All of President Trump’s Facebook ads sought a donation and some of them also promotedcampaign rallies or fundraising dinners. 

## Reports, Data and Code
- Code to scrape Twitter Ads 
- Complete Report
- Facebook Data
