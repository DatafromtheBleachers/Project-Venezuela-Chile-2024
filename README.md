# Reviewing sequence of 70+ passes made by Venezuela against Chile (Soccer)
## by Anthony Verdesca

The code helps to group of passes that lead to the third goal of Venezuela against Chile during the Conmebol Qualifications Match in 2024. 
Data was extracted making use of the tool made by FC Python.

We will answer the following questions:

1) We will check if every single player on the Venezuelan's men soccer team touched the ball during the creation of the third goal against Chile.
2) Which side of the field Venezuela moved the ball/played the most.

# Executive Summary
1. [Introduction](https://github.com/DatafromtheBleachers/Understat/new/main?filename=README.md#introduction)
2. [Methodology](https://github.com/DatafromtheBleachers/Understat/new/main?filename=README.md#methodology)
3. [Results](https://github.com/DatafromtheBleachers/Understat/new/main?filename=README.md#results)

# Introduction
FC Python is a project that aims to provide accessible resources for learning basic Python, programming, and data skills to people interested in sports. It uses football data and concepts to deliver Python skills and tools.
The interfaces connects a Youtube video and the user can define Players names, Events and location on the field by clicking on the soccer and making its best educated guess.

![image](https://github.com/user-attachments/assets/5284855a-2e7f-4583-a2df-32f4dac810f7)

Data was extracted using this video:
[youtube](https://youtu.be/7dBx-xTlrl4)


# Methodology

The process consisted in 3 stages:
1) [Collecting and Organizing the data](https://github.com/DatafromtheBleachers/Understat/blob/main/Codes/Project-Understat-Webscraping.ipynb)
2) [Data Cleaning](https://github.com/DatafromtheBleachers/Understat/blob/main/Codes/Project-Understat-Data-Cleaning.ipynb) 
3) [Data Visualization using barplots, histograms, mplsoccer and heatmaps](https://github.com/DatafromtheBleachers/Understat/blob/main/Project-Understat.ipynb)

First, lets have a look in the format of the data once is scrapped:
![image](https://github.com/user-attachments/assets/9d4b7817-98af-4101-a04d-328861636a37)

# Results

## 1) Who are the 5 most influential players for Goal Events? (Goals + Assists) ##

Leverkusen could not have gotten where they are if it was not due to the contributions of these players. It is interesting to see how accurate Álex Grimaldo was on the scoring ocassions he had, as his Goal Expectations seemed to be around ~6 Goals at most, while he outperformed generating 10! 

![image](https://github.com/user-attachments/assets/1ebb173f-c54f-445d-a3e1-171945490623)

## 2) How is the performance of the 5 most influential players during the season (Month by month and by minutes played) ##

### Month by Month ###

- Boniface was having a very prolific start of the season, but it took him a while to get back into the scoreboard after the winter break.
- Álex Grimaldo provided Assists or Goals during at least once a year. Clearly a strong and dangerous player for the rivals.

![image](https://github.com/user-attachments/assets/a204861d-cc40-4405-baa6-51275fb4fc1b)

## By Minutes Played ##
- Álex Grimaldo is a complete threat during the whole game - He is able to assist or score at any point in the match, same as Florian Wirtz.
- Special attention to the block of time between the 50th and the 70th minute, where a higher number of Boniface and Wirtz's goals/assist came up.

![image](https://github.com/user-attachments/assets/32ca2367-48c3-4da4-85b5-bae564adc1c0)

# 3) From the player that scores the most: Where does he prefers to shoot and also where does he score the most goals? #

In the case of Bayer Leverkusen: Boniface takes the first place. 

## Shot Heatmap ##

- Boniface looks to place himself in areas with near the penalty spot.
![image](https://github.com/user-attachments/assets/1248c285-241f-42c2-a7bd-209082c19640)

## Goal Heatmap ##
- Once again, although more faded, the higher amount of goals is located near the penalty spot. 
![image](https://github.com/user-attachments/assets/05ce126a-ae3e-4fbe-bb15-03d1339c9999)

# 4) Who is the best "duo" (Goals and assisted the most) #
- Victor Boniface(Goals) + Floriant Wirtz(Assists) generated the most goals.
- Second Best: Floriant Wirtz (Assists) + Victor Boniface (Assists). The pair seems to work really well together. 
- This shows that Álex Grimaldo only assisted one player out of the top 5.
![image](https://github.com/user-attachments/assets/525dd60c-9fe1-474f-a57a-ca71981c06cc)

