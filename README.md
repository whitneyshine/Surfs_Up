# Surfs_Up<br>
![Surfs_up_cover_tile](Surfs_up_cover_tile.png)<br><br>

## Background<br>

W. Avy has appreciated the analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, to determine if the surf and ice cream shop business is sustainable year-round.<br><br>


## Overview of the Analysis<br><br>
**Approach**<br>

Using Python, Pandas functions and methods, and SQLAlchemy, I have filtered the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June and December. I then converted those temperatures to a list, created a DataFrame from said list, and have generated a summary statistics.<br>

**Goal**<br>

Remembering back to previous conversations with W. Avy, he has mentioned in the past that he does not just want to see a list of data results; he wants to understand trends in the data.  In that manner, I agree with W. Avy that the overall goal is to provide insight into the temperature patterns of a specific location on Oahu where he would like to build his shop. I created a histogram from the temperature observations as this will allow us to quickly review the temperature observations we have.  This information, paired alongside the data statistics, will provide insight through visualization of the temperature analysis.  Let's not forget, the goal of the exercise is not just to crunch the numbers — it is to deliver W. Avy with facts to solidfy his impending decision and investment.<br><br>

## Results<br><br>

**June Temperatures**<br>

The results show for June that the low (minimum) temperature is 64 degrees, the high (maximum) temperature is 85 degrees, and the average (mean) temperature is ~75 degrees.<br>  

![june_stats](june_stats.png)<br>

**December Temperatures**<br>

Furthermore, the results show for December that the low (minimum) temperature is 56 degrees, the high (maximum) temperature is 83 degrees, and the average (mean) temperature is ~71 degrees.<br>

![december_stats](december_stats.png)<br>

**Three Key Differences**<br>

Looking at this plot, we can infer that a vast majority of the observations are over 65 degrees.   Because of that, let's dive into the statistical data we have complied for him pertaining to the months of June and December as well as note three key differences we have discovered.<br><br>

![june_temps_graph](june_temps_graph.png)       ![december_temps_graph](december_temps_graph.png)<br>

•	June’s mean temperature is 3.9 degrees higher than December’s mean temperature.  Now what does that mean?  With the mean temperature for June being ~75 degrees and the mean temperature registered in December calculated at ~71 degrees, these temperatures support a near year-round surf environment.<br><br>
•	We have 183 more readings from June (1,700) than we do for December (1,517).  Not knowing where those temperatures would have registered and been recorded for December, or why they were not observed, we must give thought as to if this might materially impact our statistical analysis for the month of December temperatures.<br><br>
•	The bellwether that we have discovered is that the maximum temps for June and December are remarkably close in degrees and near perfect for ice cream weather.  June has a maximum temperature of 85 degrees while December registers a maximum temperature of 83 degrees.<br><br>
•	A crucial statistic we calculated for the two months in question are the minimum temperatures.  Respectfully, the documented minimum temperature for June is 64 degrees and December records a minimum temperature of 56 degrees.  


## Summary<br><br>

Knowing the facts from above this data should not give W. Avy pause in preceding forward as the statistics endorse year-round participation for surfing and ice cream.  The statisical temperature catergories we ran for Oahu show W. Avy that the temperatures are consistently coupled within the two months analzyed.  The outside temperatures support  enjoyment will be had by all but conversely, one should ponder if the water temperatures are as predicitable and pleasant as the outside temperatures in Oahu.  What I believe W. Avy needs to consider before renting his first surfboard and/or selling his first ice cream to his first customer, would be the particulars around monthly precipitation and monthly wind speed.  In my final recommendation, I would advise running those two additional queries.<br><br>

**Precipitation**<br>

Now, let us think about precipitation. There needs to be enough rain to keep everything green, but not so much that you lose out on that ideal surfing and ice cream weather.  W. Avy's mind would be set to ease by analyzing precipitation levels and showing him the data that backs up Oahu as the perfect place to surf.<br><br>

**Wind Speed**<br><br>
Seeing that we are nearly convinced of opening the surf and ice cream shop, let us consider assessing the wind speed for Oahu.  I think it would be advantageous to replicate the statistical approach we took towards the temperatures of Oahu and apply that to consider the maximum wind speed, minimum wind speed, and mean wind speed during the months of June and December.  The last thing we want is to not be able to surf due to hazardous wind speeds as well as our ice cream getting blown off our waffle cone.<br><br>

**Recommendation**
This exercise and analysis has been turned into a solidifed and repeatable process for W. Avy. Without hesitation, I support and encourage W. Avy to move forward with his business venture.  In the future, this study ensures that the process can be duplicated when we need to figure out where to open the second surf and ice cream shop. It looks like W. Avy will be able to have his ice cream and eat it too. 

