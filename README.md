### Problem this analysis is trying to solve:
1. Is player height correlated to ability in the NBA? Is so, what is the optimal height for NBA players?
1. Is player age correlated to ability in the NFL, NBA, MLB, and NHL? If so, what is the optimal age for each sport?
1. Are there specific towns/areas that players in the NFL, NBA, MLB, and NHL are more likely to come from? If so, where?
1. Are there specific colleges that players in the NFL, NBA, MLB, and NHL are more likely to attend? Is so, which colleges?

### How to run the code:
1. Download and save the files inside of the folders "Sandy NBA & NHL", "Matt_NFL", and "MLB" to a folder on your computer.
1. Open your terminal.
1. cd into the folder you saved the files in.
1. Run the command "jupyter notebook". This will open the folder in the Jupyter Notebook website.
1. Open up the files "NBA 2019.ipynb", "NHL 2019.ipynb", "nfl_api.ipynb", "mlb.ipynb", and "mlb_msf.ipynb" on Jupyter Notebook.
1. For each file, at the top, under the "Kernal" tab, click "Restart & Run All". This will run all the cells on the page and display all the dataframes and graphs.

### Data collected:
![](Sandy%20NBA%20&%20NHL/Figures/nba%202019%20height%20boxplot.png)
![](Sandy%20NBA%20&%20NHL/Figures/height%20vs.%20points%20top%202019%20nba.png)
![](Sandy%20NBA%20&%20NHL/Figures/height%20vs.%20assists%20top%202019%20nba.png)
![](Sandy%20NBA%20&%20NHL/Figures/height%20vs.%20rebounds%20top%202019%20nba.png)
![](Sandy%20NBA%20&%20NHL/Figures/height%20vs.%20blocks%20top%202019%20nba.png)
![](Sandy%20NBA%20&%20NHL/Figures/height%20vs.%20steals%20top%202019%20nba.png)
![](Sandy%20NBA%20&%20NHL/Figures/num%20ages%202019%20nba.png)
![](Sandy%20NBA%20&%20NHL/Figures/points%20top%20100%202019%20nba.png)
![](Sandy%20NBA%20&%20NHL/Figures/assists%20top%20100%202019%20nba.png)
![](Sandy%20NBA%20&%20NHL/Figures/rebounds%20top%20100%202019%20nba.png)
![](Sandy%20NBA%20&%20NHL/Figures/blocks%20top%20100%202019%20nba.png)
![](Sandy%20NBA%20&%20NHL/Figures/steals%20top%20100%202019%20nba.png)
![](Sandy%20NBA%20&%20NHL/Figures/nba%20birth%20map.png)
![](Sandy%20NBA%20&%20NHL/Figures/nba%20college%20map.png)

### Why the data is displayed this way:
The figures above show the data just for the NBA. Very similar graphs were created for the players in the NFL, MLB, and NHL as well. A box plot was used to display the heights of height of NBA players, so you can visualize the range and median of their heights. A histogram was used to display the ages of NBA players so you can see exactly how many people there are of each age. Scatter plots with regeression lines were used to display height and age vs. various statistics to see if there were any correlations between the variables. An r^2 value was included for each scatter plot to see exactly how strong the correlations were. Lastly, heat maps were created to display the areas were atheletes of each sport were born and attended college, so we could determine if there were any hot spots players of each spot came from or went to school.
