# COMP_3125_03_Final
Final Individual Project for COMP-3125 Section 03

# Introduction:
&emsp;This project takes a look at Maritime Piracy from 2018 
to 2022. The goal of this project is to Determine the 
safety of maritime travel and trade.

Data Selection:  
&emsp;Each Data Set within this repository has been created by myself in microsoft excel. The Data I used to create the Data sets was sourced from International Maritime Bureau. Each Data Set contains multiple categories and there respective value. These values would be cleaned by removing any value that is not given (NG). These values differ from a simple value of 0 because no information was given, possibly by choice.

Citation:  
ICC International Maritime Beureau. 2022 Annual IMB Piracy and Armed Robbery Report.2023.

Methods:  
For all questions and visualizations I would use Pythons numpy, pandas, and matplotlib.  

Q1: What Ship Type is the most prone to attack?  
For question one I chose to use an unstacked bar graph. This bar graph allows me to represent all major types of ships alongside all 3 years of data that I have.

Q2: What Region of the world is most prone to Piracy and attacks?  
For question two im still debating on whether to use geopandas and shapely.geometry alongside matplotlib in order to create a world map with points showing the location of attacks.  
If this fails I aim to create a pie chart using matplotlib. This will allow me to create a visualization that helps the viewer compare each region to one another.

Q3: When are ships most likely to be attacked and does it differ by region?
For question three I intend on using a stacked bar graph in order to show how many attacks recorded. Stacked bar graphs will help the viewer compare where these attacks are taking place and how many have taken place in a specific area.
