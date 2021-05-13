# Exploratory-data-analysis: Peer-Review-Assignment-1
 The goal behind this exercise is to implement the knowledge that we learned in the beginning section of this course.
 The trifecta of this exercise: 
 1. Data and its nature 2. Load the data set 3. Plot/communicate the results
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#                                                                                Section-1
1.1 Where is the data taken from?
The source is accredited to the UC Irvine Machine Learning Repository, a popular repository for machine learning datasets.
"Individual household electric power consumption Data Set" is the title of the source.
1.2 What is the size of the data file?
20 MB (https://d396qusza40orc.cloudfront.net/exdata%2Fdata%2Fhousehold_power_consumption.zip)
1.3 What is included in the data?
Measurements of electric power consumption in one household with a one-minute sampling rate over a period of almost 4 years.
Different electrical quantities and some sub-metering values are available.
1.4 What are the variables(#) and their definition in the data?
9 Variables
1. Date: Date in format dd/mm/yyyy
2. Time: time in format hh:mm:ss
3. Global_active_power: household global minute-averaged active power (in kilowatt)
4. Global_reactive_power: household global minute-averaged reactive power (in kilowatt)
5. Voltage: minute-averaged voltage (in volt)
6. Global_intensity: household global minute-averaged current intensity (in ampere)
7. Sub_metering_1: energy sub-metering No. 1 (in watt-hour of active energy). It corresponds to the kitchen, containing mainly a dishwasher, an oven and a microwave (hot plates are not electric but gas powered).
8. Sub_metering_2: energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to the laundry room, containing a washing-machine, a tumble-drier, a refrigerator and a light.
9. Sub_metering_3: energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to an electric water-heater and an air-conditioner
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#                                                                               Section-2
2.1 What factors need to be taken into account while loading the data?
The number of rows and columns: 2,05,259 and 9 respectively. Rule of thumb is to check how much memory needs to be allocated before reading the file into R.
2.2 Which particular time span of the data are we looking at?
2007-02-01 and 2007-02-02 (Pragmatic approach: Read the data just from these dates rather than reading entire data set and subsetting to these dates)
2.3 What functions in particular could aid in your process?
1. striptime() 2. as.Date() in converting data and time variable to Date/Time domain in R.
2.4 How are missing values coded?
with symbol ?
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#                                                                             Section-3
3.1 Please reitertae the principal goal on making these plots.
To examine how household energy usage varies over a 2 day period in February 2007. These information will be conveyed by making various plots using the base plotting system
3.2 How do you connect to the Github repository for this plot?
Fork and clone the following Github repository https://github.com/rdpeng/ExData_Plotting1
3.3 Provide the file extension for the plot. Specify the # of pixels in the width and # of pixels in height.
PNG. 480 in width and 480 in height
3.4 How will you specify the plot or name it?
plot1.png, plot2.png etc
3.5 Provide the specification of the code.
R code file (plot1.R, plot2.R corresponding to each of the png file.
3.6 What are thus must in the code file?
It should be able to read the data and reproduced the plot. You must also include the code that creates the PNG file.
3.7 Where will these files be stored?
In the top level folder of the github repository.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
When done please push your repository tho Github so that Github version of your repository is up to date. There should be four PNG files and four R code files with total of 8 files in the top folder of your repo.
