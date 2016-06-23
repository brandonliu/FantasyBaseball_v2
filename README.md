# FantasyBaseball_v2

Introduction
--------------------
The previous iteration of this visualization tool focused on developing a rankings/projection system for drafting players. It worked by aggregating data in specific categories and then generating the results in a spreadsheet format for display in an RShiny application.

New:
The new application seeks to develop a framework for exploring baseball data in the following areas:
- Identifying high-value prospects
- Identifying potential high-value free agent players
- Developing original and robust player rankings

The application seeks to provide analysis tools in the following areas:
- Comparison of pitch f/x velocity data, as well as pitch movement for different pitchers. I'm also looking to rank data on pitchers to identify high-velocity, high movement pitchers.
- Looking at the statistics of balls put in play by a pitcher throwing: BABIP, groundball, flyball, HR breakdown, soft-hard-medium contact, etc.
- Looking at batter fundamentals: soft,hard,med contact; BABIP, groundball, hr/flyball ratio, exit velocity of baseball
- Advanced: performance of certain players against certain teams, players, etc.

Code base:
While the previous framework was built on an RShiny backbone, I would like to develop this as a webapplication using Python, which should be a faster model and will be easier to code and maintain. The plan is to host this through my Stanford website. 
- Looking into Django as a full-stack framework and use D3.js for the interactive visualizations

Data sources:
MLB Gameday and Fangraphs provide lots of data on all players, including very specific data on each pitch that gets thrown.
