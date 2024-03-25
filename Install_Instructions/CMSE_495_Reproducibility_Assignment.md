## CMSE 495 Reproducibility Assignment

**Introduction**

Git Repository Link: https://github.com/lafeirjo/City_Of_Grand_Rapids_Social_Impact/tree/main

For this assignment, we will be going over how to reproduce one of the visuals that is contained within the environmental metrics dashboard, specifically regarding the air quality data. There are a few primary steps that will be discusssed:

1. Where the raw data source came from
2. The cleaning/manipulation process through a Jupyter Notebook
3. How we imported the data into Power BI
4. How we created the Year by Year Air Quality Index Summary visual.

This visual is one of the foundation figures within the "Air Quality Index - Year by Year" dashboard in our "Environmental_Metrics" report. The visual shows the minimum, average, and maximum values of AQI for the City of Grand Rapids over the time span from 2014-2024.

If the required software and dependencies are needed to be installed, I point you to our Git Repository and go into "Install_Instructions" -> "Install.md." This markdown file contains all instructions for everything needed to run our project.

In terms of where the raw data was found, the website can be found here: https://aqicn.org/historical/#!city:usa/michigan/grand-rapids
If you scroll down, you will come across a selection for the type of pollutant followed by a button stating "Download this Data (CSV Format)." Select this option to access the raw data.

Alternatively, the raw data is available in our Git Repository through "Datasets" -> "Environmental_Data" -> "airQuality.csv"
If you want to run through the cleaning process, we recommend downloading the raw file from our Repository. This will ensure that the file name is correct. If you want to download the raw data from the website you can, just make sure you rename the file to "airQuality.csv". This is needed for the Jupyter Notebook to run error free.

**Cleaning and Manipulation**

*Note that this step is optional, as the cleaned data is already accessible through our Git Repository by navigating to "Datasets" -> "Environmental_Data" -> "gr_air_quality_2.csv" and downloading the csv from there.

If you would like to follow along in the process, you will need 2 files:

1. The raw data csv found in the introduction
2. The Jupyter Notebook containing the code for cleaning.

To find this Jupyter Notebook, go into the Git Repository and go under "Datasets" -> "Environmental_Data" -> "Air_Quality.ipynb" and download it.

From here, as long as the 2 files are located in the same directory, you can hit "Run All" on the notebook and it will export the same "gr_air_quality_2.csv" csv file from our Git Repository.

**Importing Data into Power BI**

Now that we have our cleaned data from the previous section, we can change focus into Power BI, which is where all our visuals are being created and stored in dashboards.

From here, we will start by downloading the "Environmental_Metrics" PBI file, which can be found in our Git Repository under "PowerBI" -> "Metrics_Dashboards" -> "Environmental_Metrics.pbix"

When using the downloaded "Environmental_Metrics" PBI file, everything will already be preloaded into the file, meaning that all data files used to create the visuals are already imported and the visuals already created. 

When opening this file, it will open right onto one of the dashboards. If you navigate to the "Air Quality Index - Year by Year" dashboard, it will show what the desired visual is meant to look like in the top left of the dashboard.

Alternatively, if for some reason this file ends up lost, deleted, or corrupted in any way, we plan to have full descriptions on how to create each visual within the Power BI reports. For now, we will just focus on how the "Year by Year Air Quality Summary" visual was made in the steps below, starting with how to import the cleaned data from the previous section.

1. To start from scratch, we will begin by opening a blank Power BI report. This can be done by just launching the Power BI desktop app and selecting "Report" under the "New" tab.

2. This will direct to a blank dashboard, from here we can now import our cleaned data by navigating to the top ribbon and selecting "Get Data." Now select the "Text/CSV" option, which will open a file explorer tab. Here, navigate to wherever the cleaned "gr_air_quality_2.csv" file is and select to import into the report. It will present a pop-up showing a preview of the data, where you will select the "Load" button to complete the import.

3. Now that the data is imported into the report, we can move into the final section, which is creating the visual.


**Creating the Visual**

To start creating the "Year by Year Air Quality Index Summary, we will look to the "Visualizations" pane and select the Line Chart icon.

Now, we go to the data pane, and select the dropdown option on the dataset to see a list of all columns in the table for use in the visual.

Select the blank visual that was dropped onto the dashboard, which will generate more options under the Visualizations pane which allow you to drag columns from the dataset to fill in the visual.

First, for the X axis, we will take the "Date" column and drag it into the designated area. Once it is there, you will want to delete the quarter, month, and day aspects to have the axis only represent the year.

As for the Y axis, we will be dragging the "AQI" column into the designated area 3 different times. This is what allows us to have all 3 lines representing the minimum, average, and maximum of the AQI. When you first drag the column into the Y axis, it will default to summarizing by the sum of AQI. To change that, we will select the down arrow on the AQI box in the Y axis area, which brings up a list of different summarizing aspects. For this visual, we select minimum, average, and maximum, alloting one per AQI box in the Y axis. 


**Formatting the Visual**

Now that we have the basic aspects of the visual in place, we can finish off by using the same formatting styles as the finished product to have completely identical graphs. To start, we need to change the names of the different lines, which can be done by going towards the bottom of the visualizations pane with the visual selected, and double clicking on the names of the lines we want to change (ex. The first change will be from Min of AQI to Minimum, and so on so forth for the other 2 names). For the rest of the formatting, we will navigate to the "Format your Visual" tab located at the top of the visualizations pane. Once here, there will be a few different transformations to do to achieve the final product.

1. Y-Axis: Under the Y-axis tab, we will be changing the axis title to "Air Quality Index"

2. Lines: If we go under the "lines" tab, we can select which lines we wish to apply the settings to. First, choose "Minimum" and we will change the line style to "dashed." We will do the same for "Maximum."

3. After selecting the general tab, we will go to Title. From here, we will:
    1. Change the title to "Year by Year Air Quality Index Summary" 
    2. Change the font size to 18.
    3. Change the background color to the hex code "F0A787"
    4. Shift the horizontal alignment to the center.
    5. Turn on a divider and change the color of the divider to black. 

4. Effects: Under the effects tab, we will do the following:
    1. Turn on the visual border, and change the rounded corner to 10px.
    2. Turn on the shadow effect.


If everything is done correct, the resulting visual will be identical to the visual premade in the Environmental_Metrics report.







