# T20-Cricket-Analysis
> To pick top 11 players based on the t20 worldcup tournament results, which was held in Oct-Nov 2022

# Table of Content
1. [Objective](#Objective)
2. [Requirement scoping](#Requirement-Scoping)
3. [Data Collection](#Data-Collection)
4.

## 1. Objective
 To create a team that will score 180 runs on an average and will defend 150 runs
 
## 2. Requirement Scoping
The players are categorized into Openers, Middle Order, Finishers, All rounders, Specialist fast bowlers.

### Openers
* To select 2 best opening batsman based on the parameter decided.
<p align="center">
<img src="https://github.com/Ignatius306/T20-Cricket-Analysis/blob/main/images/t201.png"><br>Fig:Openers parameter
</p>

### Middle Order
* To select 3 anchors or the middle order batsman.
<p align="center">
 <img src ="https://github.com/Ignatius306/T20-Cricket-Analysis/blob/main/images/Screenshot%202023-04-08%20172307.png"><br>Fig: Middle Order Parameter
 </p>

### Finishers
* To select one player for the finisher role capable to carry the match if the middle order collapses.
<p align="center">
 <img src ="https://github.com/Ignatius306/T20-Cricket-Analysis/blob/main/images/t202.png"><br>Fig: Finisher Parameter
 </p>
 
### All Rounder
* To select two players, mostly of spinners with bowling economy and decent strike rate.
<p align ="center">
<img src ="https://github.com/Ignatius306/T20-Cricket-Analysis/blob/main/images/t203.png"> <br>Fig: All Rounder Parameter
</p>

### Fast Bowlers
* To select 3 fast bowlers based on their performance.
<p align ="center">
<img src ="https://github.com/Ignatius306/T20-Cricket-Analysis/blob/main/images/Fastbowlers.png"> <br>Fig: Fast Bowlers Parameter
</p>

## 3. Data Collection
Data Collection using web scrapping from [espn website](https://www.espncricinfo.com/series/icc-men-s-t20-world-cup-2022-23-1298134)
Used Brightdata tool to scrap the data from the website. We get all the information in the form of csv files.

## 4. Data cleaning and processing
In jupyter notebook all the files are cleaned and then processed.

## 5. Data Visualisation
Using powerBI tool top 11 players are selected. 

