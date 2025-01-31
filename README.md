# Deer hunting predictor

__**Phase 1:**__    
As a deer hunter I would lIke to know which areas in my state have the most deer harvested. Some of the questions I have include.  
- How does my state DNR track deer harvest? Is it by county or some other area?  
- States that I'm interested include MN and WI. MI is a third choice.  
- Research can begin by Googleing the state DNR to see what datasets are available. Ideally, a daily count would be best.  What are the different deer seasons? (Rifle/archery/muzzle loader/etc.)  
- I would like to know how many deer were caught each day.  
- I would like to know which seasons were in effect for each day. There may be overlap between seasons. Ideally, the data will include the harvest method. If not, the team will have to decide how to allocate the values.  

This data is to be loaded into a pandas dataframe.  This dataframe will be used for further analysis.  

__**Skills developed:**__   
Requirements gathering will be a big part of this exercise. The analyst will need to do online research and possibly talk to DNR officials to find the data needed.  

__**Phase 2:**__  
As a deer hunter I would like to find the correlation between different weather patterns and how many deer were harvested.  
- For each of the days within deer season, for each of the locations tracked in my state, I would like as many weather variables as possible. This can be gotten from https://www.ncei.noaa.gov/.  
- I would like to do a correlation analysis between each location and the number of deer harvested against the weather variables for that area.  
- I want to identify which variables dempnstrate a positive (or negative) correlation.  These relations may differ between different areas.  

__**Phase 3:**__  
As a deer hunter I would like to be able to predict my chances for success on any given day for the upcoming deer season based upon predicted weather patterns.  
- Using the data from Phase 1 and Phase 2 compare the relevant factors against the predicted weather for each of the areas within the state.  
- Based on the weather for each area develop a formula to rank an areas likely hood of success between 1%-100%  
- Make a recommendation for which area to travel to for hunting.  




