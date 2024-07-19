# Reviewing sequence of 70+ passes made by Venezuela against Chile (Soccer)
## by Anthony Verdesca

The code helps to group of passes that lead to the third goal of Venezuela against Chile during the Conmebol Qualifications Match in 2024. 
Data was extracted making use of the tool made by FC Python.

We will answer the following questions:

1) Which side of the field Venezuela moved the ball/played the most.
2) We will check if every single player on the Venezuelan's men soccer team touched the ball during the creation of the third goal against Chile.

# Executive Summary
1. [Introduction](https://github.com/DatafromtheBleachers/Understat/new/main?filename=README.md#introduction)
2. [Methodology](https://github.com/DatafromtheBleachers/Understat/new/main?filename=README.md#methodology)
3. [Results](https://github.com/DatafromtheBleachers/Understat/new/main?filename=README.md#results)

# Introduction
FC Python is a project that aims to provide accessible resources for learning basic Python, programming, and data skills to people interested in sports. It uses football data and concepts to deliver Python skills and tools.
The interfaces connects a Youtube video and the user can define Players names, Events and location on the field by clicking on the soccer and making its best educated guess.

![image](https://github.com/user-attachments/assets/5284855a-2e7f-4583-a2df-32f4dac810f7)

Data was extracted using this[video](https://youtu.be/7dBx-xTlrl4)


# Methodology

The process consisted in 3 stages:
1) [Importing and Cleaning data](https://github.com/DatafromtheBleachers/ProjectVenezuelaChile/blob/main/Code/Project_VenezuelavsChile-Cleaning-Data.ipynb)
2) [Data Visualization using mplsoccer and heatmaps](https://github.com/DatafromtheBleachers/Understat/blob/main/Project-Understat.ipynb)


# Results

## 1) Which side of the field Venezuela moved the ball/played the most? ##

- Venezuela leaned more towards the left side of the field (Attacking from Left to Right), probably because Chile's player that got a red card was on that side of the field or also because Soteldo - the most skilled player in Venezuela - plays on the left wing. 

![image](https://github.com/user-attachments/assets/b92f5b75-9229-45f7-a54e-e92cd5f062eb)

I want to check the buildup pass by pass:
![Watch the video](https://github.com/DatafromtheBleachers/ProjectVenezuelaChile/blob/main/First%20Movie.mp4)



## 2) We will check if every single player on the Venezuelan's men soccer team touched the ball during the creation of the third goal against Chile.
 ##

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

