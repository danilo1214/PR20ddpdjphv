# The drug problem in Europe

## Introduction

A very controversial topic in Europe is the drug problem. With the popularity of the Internet, and the glorification on drugs in social media, drugs are more available than ever. In this report, we want to analyze the data available regarding drugs in Europe, build various prediction models, and better understand the problem.

## Deaths

The most alarming issue, regarding drugs, is the overdose deaths. In the following images we shal look at trends regarding deaths caused by drug overdoses. 

![](overdoses.png) 

## Deaths per 1000 people

On the first chart, we can see that a large majority of overdose deaths are males, and that the three leaders of overdose deaths in 1995-2017 are Germany, UK, and Italy.  On the second graph we can see the underage overdoses - which seem to be fluctuating, with a peak of 2006-2008, and a rapid decrease until 2017 - almost by half since the peak, which is very positive.  

![Deaths per 1000 people in Europe](deathsPer1kPop.png)

On the third graph we can see that if we look at the relative deaths(per population), countries like UK, Germany and Italy do not stand out as much. The problematic countries seem to be in Scandinavia, plus Estonia and Ireland.

## Drug popularity

![](pervalence.png)

We can see that the most popular drug always seems to be cannabis - obviously because of it's legality and availability throughout most of  Europe. However it seems to be decreasing from 2010-2013, and it slowly rises from 2013-2016, but never reaching its' initial dominance in 2010. This is a very worrying trend, since the other drugs listed(Cocaine, Ecstasy, LSD) are much more dangerous than Cannabis.

## Users and suppliers

![](UsersSuppliers.png)

It is interesting, because we can see almost a symmetrical graph for the users and suppliers, for all of these drugs. So if countries want to reduce the users, they need to find the illegal suppliers. Furthermore, we have constructed regression models for each country to predict the users of a drug, based on the suppliers of it in the country, and other countries. So that we can detect supply chains in Europe.

![](RFHEROIN.png)
![](ECSTASYLINREG.png)
![](RFCANNABIS.png)

## Users and deaths

It is fairly logical that based on the users we can predict the deaths that will occur, so we built a regression model that would look at the users of each drug, and predict deaths based on it. This is the result: 

![](PredvsActUsersDeaths.png)
