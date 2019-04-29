# I80HighwayData

split_time.py reads in data from the csv file, outputs data in text file for each vehicle. The output of this file are folders named like s001, s002... Each folder will contain a cv.txt which has information of the ego vehicle and ov{#}.txt files which contains the information of other vehicles that show up near the ego vehicle. 

read_data.m reads the text files generated by split_time into read_data.mat and matrix data_matrix. 

plot_road.m and plot_car1.m/plot_car2.m are helper functions to animate the enviroment. 

plot_cv.m animates the ego car with other vehicles. 
