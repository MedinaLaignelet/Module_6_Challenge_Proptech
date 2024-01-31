
#Challenge 6-Housing Rental Analysis for San Francisco#

Objective: Create coding in a Jupyter Notebook to analyze and visualize real state data for San Francisco for the years 2010 to 2016.
The code can be found in the Jupyter Lab notebook “San_Francisco_Housing.ipynb”

##Calculate and plot the housing units per year##
After importing all the Pandas libraries and dependencies, we import the data from the CSV files to be create the dataframe needed and then grouping the data by the year and calculating the mean of the Housing units to create the plot visualization which is then given the appropriate labels.
##Calculate and plot the average prices per square foot##
We utilize the dataframe created and manipulate by dropping the Housing Units column to create a new datafram showing the Price per Square Footage and Gross Rent Data.  The code then applies a line plot to show both values in the Y axis and the X axis for the years.  The objective of the line plot is to compare the trend in Sales Prices and Rent from 2010 to 2016.
##Compare the average prices by neighborhood##
The code creates a new dataframe by grouping by year and neighborhood.  We then manipulate the data to show only Sales process and Rent.  We then use a line plot to show the trend per neighborhood where the visualization allows a drop-down menu to change the neighborhood name and show the plot specific to that area.

##Build an interactive neighborhood map##
The code starts by reading a different CSV file containing the coordinates of the different neighborhoods.  The code then concatenates the neighborhood coordinates with the data frame containing all the neighborhoods real state data.  The code will reset the index and clean the data by dropping any nulls.  Lastly, we create a map using hvplot GeoViews to show both, Sales Prices per Square Foot and Rent data visually.  The map will help locate the neighborhood with the highest Sales Price and rent by showing a bigger or darker point in the map for each one of these measurements.
##Compose your data story##
Utilizing the different visualizations in the previous sections, as assessment is made of the Real State trend for the Sales Price and Rent in San Francisco between 2010 and 2016.

###Resources###
1.	 FINETCH Bootcamp class material Module 6 PyViz
2.	Bootcamp Virtual Tutor session
3.	AskBCS learning
