# Surfs_Up

## Background<br>

W. Avy has appreciated the analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, to determine if the surf and ice cream shop business is sustainable year-round.<br><br>


**Overview of the Analysis**<br><br>
Using Python, Pandas functions and methods, and SQLAlchemy, you will filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June and December. You will then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.<br>

Remember, your goal is to provide W. Avy with insight into the weather patterns of a specific location on Oahu where you would like to build your shop. One way to provide this insight is with a visualization—we'll plot the results of our precipitation analysis using Matplotlib.<br><br>

**Results**<br><br>

The results show for June that the low (minimum) temperature is 64 degrees, the high (maximum) temperature is 85 degrees, and the average temperature is ~ 75 degrees.  Furthermore, the results show for December that the low (minimum) temperature is 56 degrees, the high (maximum) temperature is 83 degrees, and the average temperature is ~ 71 degrees.<br>


W. Avy has mentioned in the past that he does not just want to see a list of data results; he wants to understand trends in the data. Because of that, let's dive into the statistical data we have complied for him.  While this data shows all the station observations, we are interested in determining temperature trends.  One trend we can observe based on this plot is that some months have higher temperatures than others.  You know just the thing that will help; you are going to create a plot of precipitation scores in chronological order. Rather than simply showing him whether it rained on a given day, you will show him how much it rained and if it was raining on the previous or subsequent days as well. Remember, your goal is not just to crunch the numbers—it's to help W. Avy really feel good about his investment.<br>

**Summary**<br><br>
This will help solidify a repeatable process and make it easier to run this analysis again—for example, when we need to figure out where to open our second surf and ice cream shop.  Now, let us think about precipitation. There needs to be enough rain to keep everything green, but not so much that you lose out on that ideal surfing and ice cream weather.  You know that you can set W. Avy's mind at ease by analyzing precipitation levels and showing him the cold, hard, data that backs up Oahu as the perfect place to surf. You have the last 12 months of precipitation data already loaded into your SQLite database, so you are ready to go.  W. Avy supplied you with the data he wants us to use and has asked you to look at a full year of data. When deciding how to parse the data, you remember that his favorite day is August 23, 2017 because it's the anniversary of the first time he ever went surfing and had ice cream on the same day. So, you decide to start the analysis there

