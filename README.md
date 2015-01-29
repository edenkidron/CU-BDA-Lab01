CU-BDA-Lab01 (again)
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

<enter>
I'm applying for PhD Marketing programs and one of the main statistical analysis themes in many of the current papers is Bayesian analysis approach. Also, I hear about Bayesian analysis methods in almost every major statistics class I have taken (applied design, statistical computing, survival analysis, time series, introduction to statistics, etc).

## Description of Data Analysis Problem That Interests Me:
<enter>
<enter>

Two summers ago I interned at a research based marketing company in Amsterdam, The Netherlands. They have designed and administrated an online survey to 1000 respondents trying to identify the ideal consumer decision journey. The consumer decision journey is the decision making process that each consumer goes through from the moment he or she decides to make a purchase till the moment of purchase. During this decision making process the consumer gathers information from various sources (Google search, amazon, retailer website, visit to the retailer store, friends and family, etc.) which are called Touch Points (TP). More specifically, TP are points in time where the consumer comes in contact with a brand in some way( product demonstration, prices on shelf, etc). The date format gathered is shown below where options represent TP. Steps represent the order in which the respondent visited these TP. The process of gathering these data was that each respondent picked ALL TP he or she used during their decision making process. Then, these TPs were shown at the bottom of the screen and each respondent ordered these TPs in the order that they used them.

For example: 
<enter> 
<enter>
- Dan is a typical consumer of vacuum. He is decided on buy a vacuum because his old one broke. At the beginning of his search he goes to his old retailer website to look at the vacuums to get a feel for the different vacuum attributes. Later he compares prices of vacuums on Google. A few days later, he decides to check the prices on amazon and eBay. He then maybe have a side conversation with his mother about the vacuum she uses. After that he attends a party at his friends' house and asks them about their vacuum. Eventually, he goes to the retail store down his street where he browses the different vacuums and asks one of the salesmen to give him a demonstration after which he makes his purchase. 

- In this example this consumer's row in the data would look like this:

<p align = "center"> ![](https://cloud.githubusercontent.com/assets/10660514/5964159/fe65ba3e-a7bf-11e4-920c-bf943182cc93.png)


Given:<enter>

- 1000 respondents (rows)
- Each respondent can choose between 0-10 options
- Each respondent ordered 0-10 options they used in their purchasing process
- Each respondent could have used each option once or twice
- Differences between steps don't have meaning

Objective:

- Find the top typical order of options 

## Example of Data:
<p align = "center"> ![](https://cloud.githubusercontent.com/assets/10660514/5894692/c39dcd76-a4d9-11e4-973a-e32e61e4c392.png)

## An example of a potential result where there exist common path(s):

<p align = "center"> ![](https://cloud.githubusercontent.com/assets/10660514/5964340/605bf7ca-a7c1-11e4-869f-5900c45da41c.png)


