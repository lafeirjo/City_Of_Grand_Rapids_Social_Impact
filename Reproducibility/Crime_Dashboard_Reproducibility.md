## Crime Reproducibility

**Introduction**

Git Reposititory Link: [GitHub Repository](https://github.com/lafeirjo/City_Of_Grand_Rapids_Social_Impact/tree/main)

For this project we created multiple Power BI dashboards. The nice thing about these dashboards is they are self reproducing. Meaning in order to recreate our work you would download the dashboard and open it in your Power BI desktop. The steps below are how to recreate one image in case you are unable to download our dashboard or something were to be imported incorrectly. Below are the main steps that we will be taking to recreate a figure in the income dashboard:

  1. Where to find the data
  2. How to import the data into Power BI
  3. How to create the 'Offenses by Month' visual
  4. How to format the visual

This visual allows us to see which months may have more criminal activity, as well as which categories of crime could see increases at specific times of the year.

If the required software and dependencies are needed to be installed, I point you to our Git Repository and go to [Install Instructions](https://github.com/lafeirjo/City_Of_Grand_Rapids_Social_Impact/blob/main/Install_Instructions/install.md). This markdown file contains all instructions for everything needed to run our project.

**Finding the Data**

1. Navigate to our teams folder
2. Once you are there follow this path 'Datasets' --> 'Crime_Data' --> 'Clean_Data'. This will get you to the folder that holds all of the files used in the creation of the Power BI dashboard. For this visual specifically, we are focusing on the 'NIBRS_DATA' and 'Month_Order' csv files.

**Importing the Data**

1. Open the desktop version of Power BI. If you don't have this installed on your device, please refer to the install instuctions above
2. Once Power BI is opened, in the upper left hand corner there is a 'Get Data' button. Click on that
3. This will pull up a list of file types. Click on 'Text/CSV'
4. This will pull up the file explorer for your device. Go back to where the cleaned crime data was and find the 'NIBRS_DATA.csv' file. Click on that file
5. Then click 'Open'. Finally click 'Load'
6. For the whole dashboard, repeat this process with every dataset. However, for this visual specifically, we only now need the 'Month_Order.csv' file.

**Creating the Visual**

1. On the left there is a 'Filters', 'Visualizations', and 'Data' tab. Open the 'Visuzalizations' tabs and click on the Clustered Column Chart figure. This will populate a blank graph.
2. Under the data tab you should see the data you imported above. Click the '>' to expand the view. This will show all of the columns. Using the month order table, drag 'Month' into the 'X-axis' position under the 'Visualizations' tab
3. Now using the 'NIBRS_DATA' table, next drag 'DATEOFOFFENSE' into the 'Y-Axis' position. This should automatically make it so that it takes a count for each month, which is what we are looking for.
4. Then, drag the 'NIBRS Category' column into the 'Legend' position.
5. Finally, take the 'Offense Description' column and drag it into 'Filters on this visual' under the 'Filters' pane. You want to make this filter so that it does not contain '0' or 'Local' descriptions. To do this, you can select all and manually unselect those 2 categories.

**Formating the Visual**

1. Under the 'Visualizations' section click the middle icon. It has a paint brush
2. Expand the 'X-axis' row then the 'Title' row. Make the title text 'Month'
3. Expand the 'Y-axis' row then the 'Title' row. Make the title text 'Number of Offenses'
4. Move to the 'General' tab
5. Expand the 'Title' row then the 'Title' row again. Make the text 'Offenses by Month'
6. Make the background color '#F0A787' and turn on the 'Divider'
7. Expand the 'Effects' Row and the 'Visual border' row.
8. Turn on the border and change the 'Rounded corners' to 10 px.
9. Turn on the shadow

Congratulations!! You have officially recreated a Power BI visual. 
