### Housing Rental Analysis For San Francisco
![image]('6-4-challenge-image.png')

# A visualization and analysis of real estate data based in San Francisco. 
* Data is read from two CSV files and used to create DataFrames

---
# Calculate and Plot the housing units per year

* Using the data, I calculate and plot the housing units per year by grouping the data by years and the Aggregating the results by the mean of the groups.
* Hvplot bar graph is used to visualize the results

---

# Calculate and plot the Avearge Sale Price per Square Foot
* Using the original DataFrame I group my data by year and average the results noting the lowest gross rent that is reported for the years that the DataFrame includes.
* I create a new DataFrame that filters out the housing_units column and only includes sale prices per square foot as well as gross rent.
* An Hvplot line graph is used to visualize data for the gross rent and sale price per square foot.

---

# Comparison of Average Sale Price Per Neighborhood

* I create a new DataFrame grouped by year and neighborhood then I aggregate the results by mean of the groups.
* I filter out the housing_units column leaving the DataFrame with sale price per Square foot and gross rent averages per year.
* I then plot using Hvplot line graph grouping by neighborhood.

---

# Building an Interactive Neighborhood Map
* Reading from a CSV file I create a new DataFrame that contains neighborhood Coordinates and assign index to Neighborhood.
* using the original DataFrame I create a new DataFrame and  group the data by neighborhood aggregating the results by the mean of the group.
* The two DataFrames are concatenated and used to create a visual
* Using Hvplot with GeoViews I create a points plot for all the new concanted DataFrame.
---
* Using the interactive map I make note of which neighborhood had the highest gross rent and highest sale price.
* I analyse the data and make note of how the rental income trend compares to the trend in sale prices.
* Using analysis I give insight on potential by and rent strategy. 


