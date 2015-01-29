CU-BDA-Lab01
===
**Due on Friday, 30 Jan @ 12:00am (end of thursday)**
<enter>

<p align = "center"> ![](https://cloud.githubusercontent.com/assets/10660514/5894465/aab189c8-a4d5-11e4-912c-c23b30e12e2c.jpg) 

### My name is <span style="color:purple">Eden Kidron</span> and I'm a <span style="color:purple">senior</span> majoring in <span style="color:purple">statistics</span> in the College of Agriculture and Life Sciences.
<enter>
<enter>

LInkedin profile: [EDEN KIDRON LINKEDIN](http://www.linkedin.com/pub/eden-kidron/62/940/427/)

## My motivation for taking Introduction to Bayesian Analysis:

<enter>
I'm applying for PhD Marketing programs and one of the main statistical analysis themes in many of the current papers is baysian analysis approach. Also, I hear about baysian analysis method in almost every major statistics class (applied design, statistical computing, survival analsyis, time series, introduction to statistics, etc).

## Description of Data Analysis Problem That Interests Me:
<enter>
<enter>

Two summers ago I interned at a research based marketing company in Amsterdam. They have designed and administrated an online survey to 1000 respondents trying to identify the ideal consumer decision journey. The consumer decision journey is the decision making process that a consumer goes through from the moment he or she decisdes to make a purchase till the moment of purchase. During this decision making process the consumer gathers information from various sources ( goolde search, amazon, retailer website, visit to the retailer store, friends and family, etc) which are called Touch Points (TP). More specifically, TP are points in time where the consumer comes in contact with the brand in some way. The date format gathered is shown below where options represent TP. Steps respresent the order in which the responded visited these TP (whether online or offline). The process of gathering these data was that each respondent picked the touchpoints he or she used during thier decision making process. Then, these options were shown at the bottom of the screen and each respondent ordered these TP in the order that he used them.

For example: Max is a typical consumer of vaccum. He is decided on buy a vaccum because his old one broke. At the begining of his search he goes to his old retailer website to look at the vaccums to get a feel for the different vaccum attributes. Later he compares prices of vaccums on google. A few days later, he decides to check the prices on amazone and ebay. He then maybe have a side conversation with his mother about the vaccum she uses. After that he attends a party at his friends' house and asks them about their vaccum. Eventually, he goes to the retail store down his street where he browses the different vaccums and asks one of the salesmen to give him a demonstration after which he makes his purchase. 

In this example this consumer's row in the data would look like this:

<p align = "center"> ![](https://cloud.githubusercontent.com/assets/10660514/5964159/fe65ba3e-a7bf-11e4-920c-bf943182cc93.png)


Given:<enter>

- 1000 respondents (rows)
- Each respondent chose between 0-20 options (TP)
- Each respondent ordered 0-20 opts they chose as sequenced steps in time 
- Each respondent could place each opt at least once and up to twice
- The number of steps each respondent could have ranked is between 0 - 40 
- Differences between steps don't have meaning

Objective:

- Find the top three most typical sequences of options 

## Example of Data:
<p align = "center"> ![](https://cloud.githubusercontent.com/assets/10660514/5894692/c39dcd76-a4d9-11e4-973a-e32e61e4c392.png)

## An example of a potential result where there exist common path(s):

<p align = "center"> ![](https://cloud.githubusercontent.com/assets/10660514/5964340/605bf7ca-a7c1-11e4-869f-5900c45da41c.png)

