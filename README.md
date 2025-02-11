"# My TDA/TDL Capstone Project" 

Method for aggregating snow data into a single daily value:

1. Get average snowfall value for each county (some counties have several sensor sites, others have few)
2. Compute weighted average of snowfall across the state (average value per county * county area / num counties)
