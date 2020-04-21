# Web-Design-Challenge-Bonus:

# This folder contains an analysis of:
The relationship between the Dow Jones Industrial Average (DJIA) and:
1.	The price of Brent Crude Oil. 
2.	The price of Gold.
3.	The Chinese Yuan to the US Dollar Exchange Rate.
4.	The Indian Rupee to the US Dollar Exchange Rate.
We analyzed data for the above relationships for the last 10 years (the time period of 04/19/2010 to 04/09/2020).

# To accomplish this analysis, we first extracted data using an API from the following website:
https://fred.stlouisfed.org/

We then used the Pandas and Matplotlib libraries to clean the data, analyze the data, run regression analyses, and plot 48 regression graphs (12 each for the 4 sets of relationships mentioned above). 

# This folder contains the following items:
#### A jupyter notebook file called “00_Extraction_with_API” which uses the API to extract data from the website mentioned above.
#### A jupyter notebook file called “01_Exploration_and_Cleanup” which uses Pandas to explore and clean the data extracted from the website.
#### A jupyter notebook file called “02_Analysis” which uses Pandas and Matplotlib to run linear regressions and generate regressions graphs for the 4 relationships being analyzed.
#### A jupyter notebook file called “csv_to_html” which uses Pandas to convert the csv file (with the underlying data for the 4 relationships) to an HTML file. 
#### A folder called Output which  has the output generated from the 4 jupyter notebook files mentioned above. 
#### A CSS file called “styles.css” which is used by the 51 HTML files in this folder.
#### 51 HTML files as follows:
#### index.html: 
This is the main html file that connects all the other files. This file can be seen at the following website:
https://pi108.github.io/Web-Design-Challenge-Bonus/
#### data.html: 
This file contains the underlying data (for the 4 relationships) that were analyzed for this project.
#### comparison.html:
This file contains a comparison of the 4 relationships on one single page.
#### 48 “visualization.html” files: 
These 48 files contain the in-depth analysis of each of the 4 relationships mentioned above.
There are 12 files for each of the 4 relationships – one file for the entire period (04/19/2010 to 04/09/2020), and 11 files for each of the individual years during that time period).
