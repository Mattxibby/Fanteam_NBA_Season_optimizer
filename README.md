This repository was used to formulate my wildcard team in fanteam's season-long NBA fantasy contest (https://www.fanteam.com/fantasy/dashboard/808701/current/13), which had a 10gbp buy in and pays out gbp30+ to the top 300 participants.
Roughly halfway through the season, I found my self around the 1300th position, with a stagnating team and thus decided to play my wildcard and used this repository to optimize my team:
I calculated the optimal team by introducing a variable I called 'value' which represents a player's value over their next highest scoring alternative (change in score/change in price)
Using this variable, I optimized my team subject to the budget I had, I repeated this process twice using data in the last 21 days and last 30 days, in order to try to weed out short term jumps in form
At the time of writing this wildcard has launched me back into contention for the paid places, placing withing the top 1000 and the top 100 in the gameweek after I played my wildcard, despite an injury to one of my premium player (Joel Embiid).
![image](https://github.com/Mattxibby/Fanteam_NBA_Season_optimizer/assets/157139305/3a880ed6-8490-47a5-ad96-b641e5fa40c1)
I am attempting to convert this code to be usable in fanteam's daily fantasy contests using player predictions found online
