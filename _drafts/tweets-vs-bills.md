---
layout: post
title:  "Tweets vs Bills"
description: Is there any correlation between how active a congressperson is on twitter, and how many bills he/she (co-)sponsored?
img: tweets-vs-bills.png
color: 37474F
author: fdis
---


We explored this question using data from [congress.gov](https://www.congress.gov), and each legistlator's twitter timeline.

For each senator or representative of the 114-th congress, we checked to see he/she owns a twitter account according to
data provided at [congress-legislators github](https://github.com/unitedstates/congress-legislators/).

Of 100 members of the senate, 90 of them have a twitter account. Of 447 memebers of the house, 378 of them have a twitter account.

To estimate the average tweets per day, we used upto 100 most recent tweets. We exclude any account with less than 5 tweets so far (two excluded).

**<Big>So,</Big>** is there any correlation between how active a congressperson is on twitter, and how many bills he/she (co-)sponsored? From the plot above, it seems not.

However, this plot is still interesting for other reasons.

First, it's clear that democrats are more active on either social media or in sponsoring bills.
In fact, of the top ten most active twitter users in the congress, seven of them are democrats.

| Name                  | Tweets per day | Party | Office  | State  |
| :-------------------: | :-------:      | :---: | :-----: | :----: |
| Clarke, Yvette D.     | 17.85          | D     | house   | NY     |
| Markey, Edward J.     | 12.23          | D     | senate  | MA     |
| Beyer, Donald S., Jr. | 11.06          | D     | house   | VA     |
| Nadler, Jerrold       | 11.04          | D     | house   | NY     |
| McGovern, James P.    | 10.84          | D     | house   | MA     |
| Ros-Lehtinen, Ileana  | 10.21          | R     | house   | FL     |
| Portman, Rob          | 10.03          | R     | senate  | OH     |
| Daines, Steve         | 9.81           | R     | senate  | MT     |
| Castro, Joaquin       | 9.37           | D     | house   | TX     |
| Schumer, Charles E.   | 9.18           | D     | senate  | NY     |

Second, there's quite a bit of spread among the members in their activity in bill-sponsoring and 
in tweeting.

