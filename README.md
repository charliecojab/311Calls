# 311Calls

By: Carlos Cojab (cac2309) and Ohad Bregman (ob2348)

This repository contains two Jupyter notebooks, Top10.ipynb and Parking.ipynb and should contain 311_Service_Request_2020.csv which is too large of a file for Github. (Please make sure this file is located inside the repository on the user computer before running the program.)

Using the csv file of 311 Calls, we are focusing on the 10011-zip code to see the most common incidents in the area and whether illegal parking is a more present than in the entire NYC area. 

The notebook Top10.ipynb get the csv data and make a Pandas Dataframe from which the top ten most common Complain Types in the given area are returned. This result is stored in the variable “top10”.

The notebook Parking.ipynb counts the number of totals complains in NYC and in the given zip code and compares it with their respective illegal parking incidents. The variable “higher_parking_proportion” returns True if the given zip code has a larger proportion of illegal parking incidents than the whole city does and returns False if not.
