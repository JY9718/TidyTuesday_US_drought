# TidyTuesday_US_drought

This is a weekly challenge from TidyTuesday https://github.com/rfordatascience/tidytuesday/blob/master/data/2021/2021-07-20/readme.md

The main purpose of this notebook is to discuss the drought in the US

The data is given in a weekly basis for 21 years, in order to show the general severity of the dorught in each state, I have used a new measure, assigning scores 
to each drought level accordingly and calculating the weighted average score.

This drought severity score is demonstrated in a bar chart and in real US map, to reach an conclusion that Western regions in the US are experiencing severe drought

The notebook also plots the number of states in drought condition, total area in different drought level and total population in different drought level.

Please note that in order to view the drought impact in the unit of year, I have define that a state is considered to be in drought in a year 
if more than 50% of its area or population is in drought conditions (in level D2-D4), and the duration lasts for more than 50% of the year
Hence, the result could be slightly different if we change the threshold (50%) 
