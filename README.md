# Module-15-Challenge
## Module 15 Challenge 

# Overview:

As the assigned Data Analyst, for this project, I will work with data visualization software called Tableau to present a business proposal for a bike-sharing company. In addition, for this analysis, as the assigned Data Analyst, I will use Pandas to change the "tripduration" column from an integer to a datetime datatype. Lastly, I will add these new visualizations to the two created (in this module) for my final presentation and analysis to pitch to investors.

**##Purpose
**
Using  the converted datatype, I will create a set of visualizations to:

    •	Show the length of time that bikes are checked out for all riders and genders

    •	Show the number of bike trips for all riders and genders for each hour of each day of the week

    •	Show the number of bike trips for each type of user and gender for each day of the week.

By the end of this module, I will be able to:
  •	Import data into Tableau.

  •	Create and style worksheets, dashboards, and stories in Tableau.

  •	Use Tableau worksheets to display data in a professional way.

  •	Portray data accurately using Tableau dashboards.


**#Files/Data
**Use the following link to download the Challenge starter code. Download the NYC CitiBike starter code.

  •	For this challenge, we'll use data from the Citi Bike program in New York City. The data you'll download will be contained in a flat file, a CSV.

  •	Go to the Citi Bike System Data page Links to an external site.. In the "Citi Bike Trip Histories" section, click the link that says "downloadable files of Citi Bike trip data."


**### Instructions
**
# Deliverable 1: Change Trip Duration to a Datetime Format (20 points)

  •	Using Python and Pandas functions, you’ll convert the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). After you convert the "tripduration" column to a datetime dataytpe, you’ll export the DataFrame as a CSV file to use for the trip analysis in Deliverable 2.

  •	Follow the instructions below to complete Deliverable 1.

  1.	Download the NYC_CitiBike_Challenge_starter_code.ipynb file into your bikesharing folder, and rename it NYC_Citibike_Challenge.ipynb.



## Module 15 Challenge 

# Overview:

As the assigned Data Analyst, for this project, I will work with data visualization software called Tableau to present a business proposal for a bike-sharing company. In addition, for this analysis, as the assigned Data Analyst, I will use Pandas to change the "tripduration" column from an integer to a datetime datatype. Lastly, I will add these new visualizations to the two created (in this module) for my final presentation and analysis to pitch to investors.

**##Purpose
**
Using  the converted datatype, I will create a set of visualizations to:

  •	Show the length of time that bikes are checked out for all riders and genders

  •	Show the number of bike trips for all riders and genders for each hour of each day of the week

  •	Show the number of bike trips for each type of user and gender for each day of the week.

By the end of this module, I will be able to:
  •	Import data into Tableau.

  •	Create and style worksheets, dashboards, and stories in Tableau.

  •	Use Tableau worksheets to display data in a professional way.

  •	Portray data accurately using Tableau dashboards.


**##Deliverables 
**
  •	Deliverable 1: Change Trip Duration to a Datetime Format

  •	Deliverable 2: Create Visualizations for the Trip Analysis

  •	Deliverable 3: Create a Story and Report for the Final Presentation

**#Files/Data
**Use the following link to download the Challenge starter code. Download the NYC CitiBike starter code.

•	For this challenge, we'll use data from the Citi Bike program in New York City. The data you'll download will be contained in a flat file, a CSV.

•	Go to the Citi Bike System Data page Links to an external site.. In the "Citi Bike Trip Histories" section, click the link that says "downloadable files of Citi Bike trip data."


### Instructions

# Deliverable 1: Change Trip Duration to a Datetime Format (20 points)

•	Using Python and Pandas functions, you’ll convert the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). After you convert the "tripduration" column to a datetime dataytpe, you’ll export the DataFrame as a CSV file to use for the trip analysis in Deliverable 2.

•	Follow the instructions below to complete Deliverable 1.

 1.	Download the NYC_CitiBike_Challenge_starter_code.ipynb file into your bikesharing folder, and rename it NYC_Citibike_Challenge.ipynb.

 ![image](https://user-images.githubusercontent.com/117233641/231678001-1d4c41f4-822a-4950-b64d-f3fcc47f67b3.png)

2.	Use the instructions below to add code where indicated by the numbered-step comments in the starter code file. We have provided the dependencies you will need for this challenge.

3.	In Step 1, create a DataFrame from the 201908-citibike-tripdata.csv file.

![image](https://user-images.githubusercontent.com/117233641/231678102-73ba09d6-2504-4776-9106-749d12792fc8.png)

![image](https://user-images.githubusercontent.com/117233641/231678270-668546c6-c7e5-4855-b75b-857f72daa1f8.png)


4.	In Step 2, check the datatypes of each column in the DataFrame.

 ![image](https://user-images.githubusercontent.com/117233641/231678328-a5350c7d-6ad9-4bf0-a02e-d5c9ec82ca5b.png)


5.	In Step 3, convert the "tripduration" column to a datetime datatype by passing the DataFrame column and the units inside the to_datetime() function.

•	NOTE: You can create a new column that contains the conversion if you don't want to change the "tripduration" column to a datetime datatype.

![image](https://user-images.githubusercontent.com/117233641/231678390-3e57a65a-de84-437e-b55e-016136f8ab27.png)
 
 ![image](https://user-images.githubusercontent.com/117233641/231678541-d2c9b8e6-1867-4195-9024-99daf7d78d22.png)

 
6.	In Step 4, check the datatypes of the DataFrame.
 
![image](https://user-images.githubusercontent.com/117233641/231678621-6ec32d4d-44bc-4e62-b6a7-0d4e11328d50.png)
 
7.	Confirm that the converted values in the "tripduration" column match the following image:

![image](https://user-images.githubusercontent.com/117233641/231678700-9ffb2305-ac53-40e9-a0e8-f41d544c24b1.png)
 


8.	In Step 5, export the DataFrame as a new CSV file without the index column. Use this new CSV file for Deliverable 2.
 
![image](https://user-images.githubusercontent.com/117233641/231678760-5bdbd128-c40a-4afa-a921-6231e512957e.png)




**##Deliverable 2: Create Visualizations for the Trip Analysis (50 points)
**
**Using Tableau, create visualizations that show:
**
  •	How long bikes are checked out for all riders and genders.

  •	How many trips are taken by the hour for each day of the week, for all riders and genders.

  •	A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

  •	Open Tableau and import the new CSV file that contains the conversion of the "tripduration" column to a datetime datatype in a new Tableau workbook.



**##Create the Checkout Times for Users Viz
**
In this visualization, you’ll graph the length of time that bikes are checked out for all riders.
1.	Add the number of records or the generated field that counts the number of records in the CSV file to the Rows.

2.	Add the "tripduration" column you converted to the Columns, and filter the "More" option by "Hour".

3.	Add the "tripduration" column again to the Columns, and filter the "More" option by "Minute", and then change the values from "discrete" to "continuous".

4.	Add the "tripduration" column that shows the "Hour" to the Filters field, and select "Show Filter".

5.	Edit the X and Y axis labels by right-clicking on the axis label and selecting "Edit Axis".

 ![image](https://user-images.githubusercontent.com/117233641/231682075-40a9ea57-b970-4fcc-877a-bd015bed7352.png)


**##Create the Checkout Times by Gender Viz
**
#In this visualization, you’ll graph the length of time that bikes are checked out for each gender.

1.	Repeat steps 1-4 of the "Checkout Times for Users" visualization.

2.	Add the converted column for gender as a color to the Marks field, add it to the Filters field, and select "Show Filter".

3.	Edit the X and Y axis labels by right-clicking on the axis label and selecting "Edit Axis".

![image](https://user-images.githubusercontent.com/117233641/231873985-3cb6486e-4355-43de-bf4d-2dd0cc0cbbb9.png)


**#Create the Trips by Weekday for Each Hour Viz

**In this visualization, you’ll graph the number of bike trips by weekday for each hour of the day as a heatmap.

1.	Add the "Starttime" column to the Rows, and filter the "More" option by "Hour".

2.	Add the "Stoptime" column to the Columns, and filter the “More” option by "Weekday".

3.	Add the number of records or the generated field that counts the number of records in the CSV file to the Marks field as a color. Select "Automatic" for the type of graph to create the heatmap.

4.	Format the Y axis of the Starttime by Hour to show the 12-hour format, as the following image:

  ## In conclusion, based on the graph labeled “Trips by Weekday,” per Hour,” indicates that “Monday, Tuesday, and Thursday are the busiest days. 
      •	  ![image](https://user-images.githubusercontent.com/117233641/231679263-cd86a759-be91-4a86-b31a-000248164cb9.png)
 
![image](https://user-images.githubusercontent.com/117233641/231682553-6950984d-a426-4053-967f-658c6eafc454.png)


**##Create the User Trips by Gender by Weekday Viz
**
In this visualization, you'll create a heatmap that shows the number of bike trips broken down by gender for each day of the week by each Usertype.

  1.	Add the converted column for "Gender" to the Columns and to the Filters field, and select "Show Filter".

  2.	Add the "Usertype" to the Rows and to the Filters field, and select "Show Filter".

  3.	Add the "Starttime" column to the Rows, and filter the "More" option by "Weekday".








4.	Add the number of records or the generated field that counts the number of records in the CSV file to the Marks field as a color. Select "Automatic" for the type of graph to create the heatmap.

![image](https://user-images.githubusercontent.com/117233641/231679794-177cec48-4289-433e-8a0a-2bc3382ee22a.png)

 

###Deliverable 3: Create a Story and Report for the Final Presentation (30 points)

Requirements”

1.	You must use the five visualizations that you created in Deliverable 2.

2.	You must use at least two visualizations that you created in this module.

3.	In your README markdown file, include the following:
o	Overview of the analysis: Explain the purpose of this analysis.
o	Results: Using the visualizations you have in your Tableau Story, describe the results of each visualization underneath the image.
o	Summary: Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset.

See “detailed” answers below

##Requirements


 
 




##Deliverable 3: Create a Story and Report for the Final Presentation (30 points)

#OVERVIEW:
(As captured from Data Bootcamp Module 15) 

In this module, as assigned Data Analyst, I will analyze, produce data visualization, and illustrate statistical skills by retrieving and analyzing weather data for a hypothetical travel company, PlanMyTrip. Successfully completing the tasks will draw on your knowledge of Python, decision and repetition statements, data structures, Pandas, and Matplotlib.


#PURPOSE

For this analysis, I will use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

•	Show the length of time that bikes are checked out for all riders and genders

•	Show the number of bike trips for all riders and genders for each hour of each day of the week

•	Show the number of bike trips for each type of user and gender for each day of the week.

Finally, I will add these new visualizations to the two created in this module for your final presentation and analysis to pitch to investors. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

![image](https://user-images.githubusercontent.com/117233641/231680783-55258b86-1277-4710-b45a-c535d4562aea.png)


1.	Results:
o	There are at least seven visualizations for the NYC Citibike analysis (7 pt)

o	There is a description of the results for each visualization (7 pt)

•	Males were significantly higher users than other demographics.

 

•	6-10 am and 5-8 PM are peak riding hours during the weekday and 5 am to 10 pm on the weekends.
o	See Worksheet labeled Trips (Weekday per Hour)


 


•	Males were high users during the peak hours. 
•	Males subscribers were the largest usertype by gender
o	See Worksheet labeled “Trips by Gender (Weekday per Hour)”

 

**2.	Summary:
**
•	Future data analysis should include a geographical analysis where Tableau displays could be expanded to illustrate the weather conditions that are currently tracked in this analysis.

•	Add a Dashboard:

The primary function of dashboards is not necessarily to tell a story, but rather to organize and view data in a central location. Dashboards allow us to share data in a way our audience will easily understand, rather than simply showing them a bunch of worksheets.

 

•	Add a new chart/ worksheet to visually show the “Number of Rides per Hour.” This newly created chart/worksheet, used in conjunction with the existing chart labeled “Trips by Weekday per Hour,” may offer additional data analysis which can assist management and logistics in refining their staffing model, accordingly. 

o	6-10 am and 5-8 PM are peak riding hours during the weekday, and 5 am to 10 pm on the weekends.

o	Non-peak hours are 1-5 am.
Suggestion: Bike Repairs could be planned during Non-Peak hours. 


 

 




2.	Use the instructions below to add code where indicated by the numbered-step comments in the starter code file. We have provided the dependencies you will need for this challenge.

3.	In Step 1, create a DataFrame from the 201908-citibike-tripdata.csv file.


 

 

4.	In Step 2, check the datatypes of each column in the DataFrame.

 

5.	In Step 3, convert the "tripduration" column to a datetime datatype by passing the DataFrame column and the units inside the to_datetime() function.

•	NOTE: You can create a new column that contains the conversion if you don't want to change the "tripduration" column to a datetime datatype.
 

 

6.	In Step 4, check the datatypes of the DataFrame.
 
7.	Confirm that the converted values in the "tripduration" column match the following image:

 

EP DIVE
8.	In Step 5, export the DataFrame as a new CSV file without the index column. Use this new CSV file for Deliverable 2.
 




##Deliverable 2: Create Visualizations for the Trip Analysis (50 points)

Using Tableau, create visualizations that show:

•	How long bikes are checked out for all riders and genders.

•	How many trips are taken by the hour for each day of the week, for all riders and genders.

•	A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

•	Open Tableau and import the new CSV file that contains the conversion of the "tripduration" column to a datetime datatype in a new Tableau workbook.



Create the Checkout Times for Users Viz

In this visualization, you’ll graph the length of time that bikes are checked out for all riders.
1.	Add the number of records or the generated field that counts the number of records in the CSV file to the Rows.

2.	Add the "tripduration" column you converted to the Columns, and filter the "More" option by "Hour".

3.	Add the "tripduration" column again to the Columns, and filter the "More" option by "Minute", and then change the values from "discrete" to "continuous".

4.	Add the "tripduration" column that shows the "Hour" to the Filters field, and select "Show Filter".

5.	Edit the X and Y axis labels by right-clicking on the axis label and selecting "Edit Axis".

 

##Create the Checkout Times by Gender Viz

#In this visualization, you’ll graph the length of time that bikes are checked out for each gender.

1.	Repeat steps 1-4 of the "Checkout Times for Users" visualization.

2.	Add the converted column for gender as a color to the Marks field, add it to the Filters field, and select "Show Filter".

3.	Edit the X and Y axis labels by right-clicking on the axis label and selecting "Edit Axis".


 


#Create the Trips by Weekday for Each Hour Viz
In this visualization, you’ll graph the number of bike trips by weekday for each hour of the day as a heatmap.

1.	Add the "Starttime" column to the Rows, and filter the "More" option by "Hour".

2.	Add the "Stoptime" column to the Columns, and filter the “More” option by "Weekday".

3.	Add the number of records or the generated field that counts the number of records in the CSV file to the Marks field as a color. Select "Automatic" for the type of graph to create the heatmap.

4.	Format the Y axis of the Starttime by Hour to show the 12-hour format, as the following image:

In conclusion, based on the graph labeled “Trips by Weekday,” per Hour,” indicates that “Monday, Tuesday, and Thursday are the busiest days. 
•	
 

5.	Optional: Format the X axis of Stoptime by Weekday as "Abbreviation".



##Create the User Trips by Gender by Weekday Viz

In this visualization, you'll create a heatmap that shows the number of bike trips broken down by gender for each day of the week by each Usertype.

1.	Add the converted column for "Gender" to the Columns and to the Filters field, and select "Show Filter".

2.	Add the "Usertype" to the Rows and to the Filters field, and select "Show Filter".

3.	Add the "Starttime" column to the Rows, and filter the "More" option by "Weekday".

4.	Add the number of records or the generated field that counts the number of records in the CSV file to the Marks field as a color. Select "Automatic" for the type of graph to create the heatmap.


 

###Deliverable 3: Create a Story and Report for the Final Presentation (30 points)

Requirements”

1.	You must use the five visualizations that you created in Deliverable 2.

2.	You must use at least two visualizations that you created in this module.

3.	In your README markdown file, include the following:
o	Overview of the analysis: Explain the purpose of this analysis.
o	Results: Using the visualizations you have in your Tableau Story, describe the results of each visualization underneath the image.
o	Summary: Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset.

See “detailed” answers below

##Requirements

 #Deliverable 3: Create a Story and Report for the Final Presentation (30 points)

#OVERVIEW:
(As captured from Data Bootcamp Module 15) 

In this module, as assigned Data Analyst, I will analyze, produce data visualization, and illustrate statistical skills by retrieving and analyzing weather data for a hypothetical travel company, PlanMyTrip. Successfully completing the tasks will draw on your knowledge of Python, decision and repetition statements, data structures, Pandas, and Matplotlib.


#PURPOSE

For this analysis, I will use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

•	Show the length of time that bikes are checked out for all riders and genders

•	Show the number of bike trips for all riders and genders for each hour of each day of the week

•	Show the number of bike trips for each type of user and gender for each day of the week.

•	Finally, I will add these new visualizations to the two created in this module for your final presentation and analysis to pitch to investors. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

1.	Results:
•	Males were significantly higher users than other demographics.

![image](https://user-images.githubusercontent.com/117233641/231873283-76ab9058-faa4-47fe-bcdb-4ff27571de60.png)

•	6-10 am and 5-8 PM are peak riding hours during the weekday and 5 am to 10 pm on the weekends.
  o	See Worksheet labeled Trips (Weekday per Hour)

![image](https://user-images.githubusercontent.com/117233641/231873355-cb8279fc-c8b9-4c5e-8cb7-16c75566a88b.png)


•	Males were high users during the peak hours. 

•	Males subscribers were the largest usertype by gender
    o	See Worksheet labeled “Trips by Gender (Weekday per Hour)”

 ![image](https://user-images.githubusercontent.com/117233641/231873415-99a94da2-b55e-450f-8f9d-646739822678.png)


2.	Summary:

•	Future data analysis should include a geographical analysis where Tableau displays could be expanded to illustrate the weather conditions that are currently tracked in this analysis.

•	Add a Dashboard:

The primary function of dashboards is not necessarily to tell a story, but rather to organize and view data in a central location. Dashboards allow us to share data in a way our audience will easily understand, rather than simply showing them a bunch of worksheets.

![image](https://user-images.githubusercontent.com/117233641/231873552-badd8c22-368c-4d9e-adf3-db286605b9d2.png)
 

•	Add a new chart/ worksheet to visually show the “Number of Rides per Hour.” This newly created chart/worksheet, used in conjunction with the existing chart labeled “Trips by Weekday per Hour,” may offer additional data analysis which can assist management and logistics in refining their staffing model, accordingly. 

o	6-10 am and 5-8 PM are peak riding hours during the weekday, and 5 am to 10 pm on the weekends.

o	Non-peak hours are 1-5 am.

Suggestion: Bike Repairs could be planned during Non-Peak hours. 

![image](https://user-images.githubusercontent.com/117233641/231873702-e9d66578-5b36-4c73-8b8b-be300bd81295.png)

 

 


