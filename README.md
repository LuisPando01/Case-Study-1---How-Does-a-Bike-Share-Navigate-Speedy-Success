<h1>Bike-Share Company Data Analysis</h1>

<h2>Description</h2>
This project sonsist on working with a dataset of bike rides in 2022, in order to discover insights (metrics) that could benefit the company. There are three R files, each one consist on a main phase of the project, these are: data preparation, data cleaning and data analysis. This file explains the content of each one and the result.

<h2>Data download</h2>

https://divvy-tripdata.s3.amazonaws.com/index.html
<br />

<h2>Content</h2>

- <b>[Phase 1: Data Preparation](#phase-1-data-preparation)</b>
- <b>[Phase 2: Data Cleaning](#phase-2-data-cleaning)</b>
- <b>[Phase 3: Data Analysis](phase-3-data-analysis)</b>
- <b>[Conclusion](#conclusion)</b>

<h2>Phase 1: Data Preparation</h2>

To start the job, activate the libraries we are going to use for these project. If you don't have, you can install them with the command install.packages("#Name_of_the_library#").
Import the data and verify the number and names of the colums. In order to combine the data, all files must have the same column names.
Combine the data and validate.

<h2>Phase 2: Data Cleaning</h2>

Remove data that is going to bias the analysis, for example:
- <b>Missing values (NA).<b>
- <b>Duplicates.<b>
- <b>Mistakes on data input (Unreal values).<b>
<br/>
Separate the date and time for a better analysis and add a ride lenght column, this is going to be the main attribute to analyse.<br />
Select the useful data and save it in a csv. file.

<h2>Phase 3: Data Analysis</h2>

Show the basic statistical values of the ride length and compare them between casual users and member users.<br/>
Show the following metrics and graphics:
- <b>Rides data by type and weekday.<b>
- <b>Visualization for number of rides.<b>
- <b>Visualization for average duration of rides.<b>
- <b>Rider length data by customer type and month.<b>

<h2>Conclusion</h2>

- <b>Less rides in the winter months.<b>
- <b>More ride duration for casual and members on friday and saturday.<b>
- <b>The ride duration of casual riders increase almost double on fridays and saturdays.<b>
- <b>From monday to tuesday, there is double the ride of members compared to casual ones.<b>
- <b>On friday, saturday and sunday, the number of rides of casual and members is the same.<b>


The company could make a marketing campaign with the goal to increase members targeting casual riders by offering more benefits of a ride on friday, saturday and sunday, when they use more this service.


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
