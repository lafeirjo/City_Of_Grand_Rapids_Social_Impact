## Income Reproducibility

**Introduction**

Git Reposititory Link: [GitHub Repository](https://github.com/lafeirjo/City_Of_Grand_Rapids_Social_Impact/tree/main)

For this project we created multiple Power BI dashboards. The nice thing about these dashboards is they are self reproducing. Meaning in order to recreate our work you would download the dashboard and open it in your Power BI desktop. The steps below are how to recreate one image in case you are unable to download our dashboard or something were to be imported incorrectly. Below are the main steps that we will be taking to recreate a figure in the income dashboard:

  1. Where to find the data
  2. How to import the data into Power BI
  3. How to create the 'Elevated Blood Levels by Year' visual
  4. How to format the visual

This visual allows us to look at the trends of elevated blood levels in children for a few different types of blood lead level tests.

If the required software and dependencies are needed to be installed, I point you to our Git Repository and go to [Install Instructions](https://github.com/lafeirjo/City_Of_Grand_Rapids_Social_Impact/blob/main/Install_Instructions/install.md). This markdown file contains all instructions for everything needed to run our project.

**Finding the Data**

1. Navigate to our teams folder
2. Once you are there follow this path 'Datasets' --> 'Health_Data' --> 'Clean_Data'. This will get you to the folder that holds all of the data used to create this dashboard. For this visual, we will be focusing on the 'HE_-_Percent_of_Children_with_Elevated_Blood_Lead_Levels_20240127_cleaned.csv' dataset.

**Importing the Data**

1. Open the desktop version of Power BI. If you don't have this installed on your device, please refer to the install instuctions above
2. Once Power BI is opened, in the upper left hand corner there is a 'Get Data' button. Click on that
3. This will pull up a list of file types. Click on 'Text/CSV'
4. This will pull up the file explorer for your device. Go back to where you had the 'HE_-_Percent_of_Children_with_Elevated_Blood_Lead_Levels_20240127_cleaned.csv' file. Click on that file
5. Then click 'Open'. Finally click 'Load'
6. If something were to go wrong with the dashboard, you can import the rest of the data using the same steps as above. (Note: some datasets used in this dashboard are located in the 'Raw_Data' section rather than 'Clean_Data')

**Creating the Visual**

1. On the left there is a 'Filters', 'Visualizations', and 'Data' tab. Open the 'Visuzalizations' tabs and click on the line plot figure. This will populate a blank graph
2. Under the data tab you should see the data you imported above. Click the '>' to expand the view. This will show all of the columns. Drag 'Year' into the 'X-axis' position under the 'Visualizations' tab
3. Next, drag all of the 'CEBLL', 'EBLL', and 'VEBLL' columns into the 'Y-Axis' position. These should automatically populate as 'sum', which is what we are looking for.'
6. In the 'Visualizations' tab there are three icons. Click on the icon that looks like a magnifying glass
7. Where it says 'Trend Line', turn that to on.

**Formating the Visual**

1. Under the 'Visualizations' section click the middle icon. It has a paint brush
2. Expand the 'X-axis' row then the 'Title' row. Make the title text 'Year'
3. Expand the 'Y-axis' row then the 'Title' row. Make the title text 'Sum of Elevated Blood Levels'
4. Move to the 'General' tab
5. Expand the 'Title' row then the 'Title' row again. Make the text 'Elevated Blood Levels by Year'
6. Make the background color '#F0A787' and turn on the 'Divider'
7. Expand the 'Effects' Row and the 'Visual border' row.
8. Turn on the border and change the 'Rounded corners' to 10 px.
9. Turn on the shadow

Congratulations!! You have officially recreated a Power BI visual. 
