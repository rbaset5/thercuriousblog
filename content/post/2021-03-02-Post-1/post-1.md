---
title: "How is data science used in sports analytics and how can it be used as a useful tool in basketball?"
author: ''
date: '2021-03-02'
slug: []
categories: ["Pistons"]
tags: ["Sports", "Basketball", "Analytics"]
draft: yes
---


I recently started reading the book [Basketball Data Science with applications in R](https://www.routledge.com/Basketball-Data-Science-With-Applications-in-R/Zuccolotto-Manisera/p/book/9781138600799) by Paola Zuccolotto_ Marica Manisera professors of statistics at the University of Berscia. According to its publisher the book is arguably one of the first to provide statistical and data mining methods for the growing field of analytics in basketball. 

## The wrong way of understanding sports analytics. 

A good way of knowing its importance is understanding the wrong way of using sports analytics. It turns out a vast majority of people believe that statistics in basketball can be reduced to counting the number of shots, baskets, points, assists, turnovers, etc. Often you'll read of stats detected in NBA games with fans excited to bet on players exceeding first and all-time records. However, sensationalist claims using counts of assists, points and steals as a thermometer to gauge player's skills. Surely, to evaluate performance only thee basis of these values is not only very reductive but even, in some cases, misleading. Additionally, players can change their way of playing with the goal of keeping high stats at the detriment to teamwork with the only real goal of winning. The authors go on to state that the most important facts of basketball are not measured by statistics but they could be measured by statistics and, in general, by Data Science. 

The authors go on to question the practicality of using numbers to describe the game..."How do we measure aspects like the way a point guard is able to control the pace of a game and his decision-making skills, the influence of a leader on the team's self-confidence, the cohesion of the players, the extent to which defense is firm and touch, etc.?". 

For a Statistician, these are simply questions about data that, collected in large quantities and appropriately re-elaborated, can be transformed into useful information to support technical experts in their decisions. 

In subsequent posts I'll be using R to explore the data and statistics behind my home-town and favorite sports team on the planet, the basketball team Detroit Pistons, while trying not to reduce the game to numbers that are not truly able to describe it. I'm interested in concentrating on the issues related to the players, the playing patterns, the games and the factors influencing performance. 

Following the direction of the book, we will limit ourselves to cite common analytics based on the concepts of possession and pace. Additionally, we will be dealing with tools of descriptive statistics applied to basketball data: 
*   Bar and radial plots built using game variables
*   Percentages or other standardized statistics 
*   Scatter plots of two selected variables, 
*   Bubble plots to represent several features of teams or players in a unique graph
*   Variability and inequality indexes and graphs
*   Shot charts with the court split into sectors colors according to a selected game variable and annotated with scoring percentages


