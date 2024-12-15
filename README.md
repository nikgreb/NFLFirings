# Is it Worth it to Fire Your Coach in the NFL?
Final Project for Professor Schueller's Intro to Data Science Class



## Group Members
Nik Greb, Matt Mascavage, Owen Kim

## Coding Worksheet
This is the worksheet that our group worked from for the data analysis of our project:
![Colab Worksheet](https://github.com/nikgreb/NFLFirings/blob/783adf0d989ee371a8b2313a0f4daec6a561c964/Data_Science_Final_Project.ipynb)

### Introduction
We created our own custom data set by compiling statistics collected from a number of sources. The final data set contained the following info from the 2002 - 2023 NFL seasons (we chose this range because the 32nd team, the Texans, were added to the League in 2002):
* Year - The season for that entry
* Coach - The head coach for that season 
* There will be separate entries if a coach was fired and replaced midseason, one entry for each coach
* This way, the rest of the data all applies to the team’s performance under that specific coach
* Team - The team for that entry
* Games Played - The number of games played under that coach
* Wins
* Losses
* Ties
* Win Percentage - Calculated as wins/games
* Points Scored
* Points Against
* Point Differential - Points scored minus points against

Creating this data set was the bulk of the work for this project. We had to combine data from multiple sources and often had to enter the data manually (this was the case for every year where a team had multiple head coaches in a season). Once we had created the data set, the goal was to look at some of the different measures of a team’s performance and compare that to the changes in coaching. Some of the questions we were hoping to answer were:
* Does firing a coach and hiring a new one boost the team’s performance? Is it “worth it?”
* How do teams who change head coaches often compare in performance to teams that keep the same coach for a long period of time?

Naturally, there are a lot of confounding factors at work, but we’re really just trying to capture the relationship between coaching changes and team performance.

Data sources: 
* https://www.pro-football-reference.com/years/2023/coaches.htm

  This source was used to find head coaches for each team for a given year. For years with a midseason firing, it showed the week that the firing occurred and how many wins each coach had that season. 

* https://www.pro-football-reference.com/years/2008/index.htm

For seasons with midseason firings, we used this data source to calculate “Points Scored” and “Points Against”, which were then used to find “Points Differential.” We used this data source to check game by game data for a team that had a midseason firing, manually calculating the “Points Scored” and “Points Against” from before and after the firing. 

* https://www.nfl.com/stats/team-stats/

This is the official NFL website and it had really complete (and reliable) statistics on team performance. We mostly used it to find each team’s record for all of the seasons and to catch tie scores for the “Tie” column.
Wikipedia - We used wikipedia to make the coaches column, finding all of the coaches for each team for any given year. We would search “[NFL team] head coach history” and wikipedia would provide each head coach for the given team, and also the years when they were the head coach. Midseason firings were shown by two coaches in a single year. 


Put the contents of your report from Part II.
Export visualizations from your colab worksheet and embed them in the appropriate locations in your report.






















