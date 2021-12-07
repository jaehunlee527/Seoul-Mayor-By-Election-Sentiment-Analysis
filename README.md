# Seoul Mayor By-Election Sentiment Analysis

## Background
April 7th, 2021 was the day of by-election in South Korea that shook the current political landscape, in the passage to presidential election slated to take place in less than a year; Democratic Party, currently occupying majority seats in the national assembly, have lost in the mayor elections in Seoul and Busan, two largest cities in South Korea. A huge landslide victory for People Power Party (Republican) has sprouted the hopes of retrieving the presidency next year. 

The notable aspect of this year's elections was the prevalence of political opinions & voices on the internet - even the campaigns were allocating big chunk of their resources on social media. By now, it has become unquestionable that political sentiments in online spaces determine the outcome of the voting day. That is why there have been numerous researches involving NLP and massive text data to read the public inclination in the political realm. In fact, some were successful in predicting the unlikely winner. (like in 2016 U.S presidential election)

## Winner on April 7th
Before the by-election, I came to wonder: is there a way to measure the degree of support/hatred to particular candidates in the online space - and eventually predict the winner? I turned my attention to YouTube, now one of the most visited platforms by South Koreans - regardless of their age groups. Alhough it may be impossible to create a model that predicts the winner due to the limitation of data sets, I may be able to see the overall sentiments of the public. 

## Methods
I created a scraper that scrapes information of each video on Youtube, that appears as a result of user search keyword. It includes not only the title of each video, but also simple statistical information like number of views, likes, dislikes and comments. Through visualizing these simple statistics, we could infer people's interests & opinions toward particular topics and people. For this particular project of course, I scraped videos that appeared as a result of two candidates names as keyword: "Oh Se Hoon" (오세훈) & "Park Young Sun" (박영선).

## Code & Package Used
* Python Version: 3.7
* Packages: numpy, pandas, matplotlib, seaborn
* API: googleapiclient(youtube)
