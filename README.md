#PS239T-Final-Project

#Short Description
#Drawing from yearlong FitBit data, this code provides the foundation for preliminary analysis of the data. The variables analyzed in this code regard sleeping duration and sleep efficiency, calories burned and distance tracked as well as looking at the data by seasons. 

#The code is divided into three main sections: (1) set up, (2) plotting the data, and finally, (3) analyzing the data with some basic regressions. The first section deals with cleaning two separate datasets, for fitbit activity and fitbit sleep data, and merging them together. The second section plots the data organized around themes (activity, sleep, by seasons, etc.). And the final section provides code for the basic linear regressions models run to test relationships between variables.

#Dependencies
#R, version 3.3.1

#Files
#Data
# 1. activity.csv - data for activity measured by fitbit, includes variables for:
#date, steps, distance, calories burned, floors, minutes (by intensity), and activity calories burned.
# 2. sleep.csv - data for sleep measured by fitbit, includes variables for:
#date, minutes of sleep, minutes awake, number of awakings, number of total "rest" minutes.
# 3. fitbitdata.csv - merged dataset of activity.csv and sleep.csv.

#Code
#01_setup.R - cleaning two separate datasets, fitbit activity and fitbit sleep data, and merging them together.
#02_plotting.R -  plots the data organized around themes (activity, sleep, by seasons, etc.).
#03_regressions.R - basic linear regressions models run to test relationships between variables.

#Results
#.jpeg


#More information
#Creator: Nallely Mejia nmejia@berkeley.edu
#Course Instructor Fall 2016: Rachel Bernhard rbernhard@berkeley.edu
