# COMP_3125_03_Final
Final Individual Project for COMP-3125 Section 03

# Introduction:
&emsp;This project takes a look at Maritime Piracy from 2018 
to 2022. The goal of this project is to Determine the 
safety of maritime travel and trade while trying to predict the amount of pirate attacks in 2023. 

Data Selection:  
&emsp;Each Data Set within this repository has been created by myself in microsoft excel. The Data I used to create the Data sets was sourced from International Maritime Bureau. Each Data Set contains multiple categories and there respective value. These values would be cleaned by removing any value that is not given (NG). These values differ from a simple value of 0 because no information was given, possibly by choice.

Citation:  
ICC International Maritime Beureau. 2022 Annual IMB Piracy and Armed Robbery Report.2023.
Singapore Straight Image. Google Maps.2023

Methods:  
For my questions and visualizations I would use Pythons numpy, pandas, matplotlib and sklearn.linear_model. numpy, pandas, and matplotlib would be used in conjuncture to access and manipulate data and create visuals. sklearn.linear_model would be used for machine learning linear regression models.

Q1: Based off of known attacks on different ship types from 2018 to 2022, how many attacks will happen to those ship types in 2023?  

Through my code I was able to estimate the amount of pirate attacks on different ship types. What I found was that most ship types will see a decrease in pirate attacks. This drop can be due to an increase in patrols by local law enforcement or anti piracy operations by the navies of different countries. The ship types that did not see any real change can be explained by the lack of law enforcement in certain parts of the world.   
Note: The results will be slightly skewed until new information is released due to the recent attacks near the end of 2023

Q2: What Countries in South East and East Asia are most prone to Pirate attacks and which ountries will see an increase in attacks?  

For question two I found that overall the waterways around most asian countries are becoming continuously safer in regards to pirate attacks. My estimates show, with the exception of the Singapore Straights that Pirate attacks would decrease to almost none in 2023. Vietnam and the Philipines would see little to no change in attacks in the 2023 estimate. Its easy to see why the Singapore Straights is a hotbed for pirate attacks because it is a narrow straight which is vital for global trade and the quick movement of products/materials. 

Q3: When are ships most likely to be attacked and how does it compare to other times?  

After estimating likelyhood of attack and visualizing my findings. It would become evident that ships are mainly attacked while steaming (on there way to a location) with a 45% likelyhood. followed by at anchor (anchor dropped and ship not moving) with a 44% likelyhood. Lastly we have Ships Berthed (Typically when ships are tied up in a port to unload and load cargo) with 11%. When comparing these values a common theme between a ship at anchor and a ship steaming becomes a likely reason. At both of these points a ship can be out at sea or far from the safety of a port allowing for pirates to approach and board vessels. Unlike these two, when a ship is at berth is is commonly at a port that has maritime police or coast guard keeping an eye on possible pirate attacks and patrolling the waters.