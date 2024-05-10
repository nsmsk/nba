# NBA Drafts Analysis Project (1950-2006)

## Project Overview
This project considering the entire careers of NBA players drafted from 1950 to 2006. We focus on those drafted before 2006 to ensure a complete career view. Active players like LeBron James (drafted in 2003), Chris Paul (2005), PJ Tucker, and Kyle Lowry (2006) do not affect our analysis since their early career data is still valuable.

## Dataset 
The dataset for this project was collected using custom script `get_nba_data.ipynb`. The data was gathered from [Basketball Reference](https://www.basketball-reference.com/) using the BeautifulSoup library and then cleaned using Pandas.
Clean dataset is also available (`nba_drafts_data.csv`) and can be accessed for further analysis.

## Questions
Through this dataset, we explore various aspects of the NBA draft and players progression, focusing on:
1. The number of NBA-drafted players who played vs. those who did not play in the NBA (drafts 1950-2006).
2. Annual trends in the number of players drafted (1950-2006).
3. Comparative analysis of players drafted vs. those who played in the NBA by year (1950-2006).
4. Identification of the lowest draft pick to ever play in the NBA.
5. Top 20 career scorers (10,000+ points) drafted below the 30th pick.
6. Distribution of players scoring over 10,000 points by draft pick.
7. Universities with the most NBA-drafted players.
8. NBA teams with the most top 3 draft picks.
   
## Interactive Visualizations
Due to GitHub's limitations on viewing interactive graphs created with Plotly, I've included several PNG images of these graphs for quick reference. For a full interactive experience, you can run the code in `drafts_analysis.ipynb` on Google Colab, which will allow you to generate and interact with all the visualizations described in this project.

![newplot (1)](https://github.com/nsmsk/nba/assets/85869776/547ae6a1-6ee9-49da-8a48-fb89ef842fcd)
![newplot (2)](https://github.com/nsmsk/nba/assets/85869776/2aa30e38-a454-41db-8213-c10472a32d60)
![newplot (3)](https://github.com/nsmsk/nba/assets/85869776/76ac92d7-852d-4e86-8a7f-8d1b762ebc6d)


