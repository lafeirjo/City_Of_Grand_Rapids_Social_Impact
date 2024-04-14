## Income Reproducibility

**Introduction**

Git Reposititory Link: [GitHub Repository](https://github.com/lafeirjo/City_Of_Grand_Rapids_Social_Impact/tree/main)

For this project we created multiple Power BI dashboards. The nice thing about these dashboards is they are self reproducing. Meaning in order to recreate our work you would download the dashboard and open it in your Power BI desktop. The steps below are how to recreate one image in case you are unable to download our dashboard or something were to be imported incorrectly. Below are the main steps that we will be taking to recreate a figure in the income dashboard:

  1. Where to find the data
  2. How to import the data into Power BI
  3. How to create the 'Median Salary for Female and Male' visual
  4. How to format the visual

This is a crucial visual for the 'Income' sheet in the 'Grand_Rapids_Income_Dashboard'. This visual shows the estimated median salary for male and females in the City of Grand Rapids from 2010-2022. 

If the required software and dependencies are needed to be installed, I point you to our Git Repository and go to [Install Instructions](https://github.com/lafeirjo/City_Of_Grand_Rapids_Social_Impact/blob/main/Install_Instructions/install.md). This markdown file contains all instructions for everything needed to run our project.

**Finding the Data**

1. Navigate to our teams folder
2. Once you are there follow this path 'Datasets' --> 'Income_Data' --> 'Clean_Data'. This will get you to the folder that holds 'GR_median_salary.csv' 3. If you hover over that file three dots '...' will apear to the right. Right click on those dots. This will bring up more options
3. In the more options click 'Download'. This will download the file to your local device

**Importing the Data**

1. Open the desktop version of Power BI. If you don't have this installed on your device, please refer to the install instuctions above
2. Once Power BI is opened, in the upper left hand corner there is a 'Get Data' button. Click on that
3. This will pull up a list of file types. Click on 'Text/CSV'
4. This will pull up the file explorer for your device. Find where you downloaded the 'GR_median_salary.csv" file. Click on that file
5. Then click 'Open'. Finally click 'Load'

**Creating the Visual**

1. On the left there is a 'Filters', 'Visualizations', and 'Data' tab. Open the 'Visuzalizations' tabs and click on the line plot figure. This will populate a blank graph
2. Under the data tab you should see the data you imported above. Click the '>' to expand the view. This will show all of the columns. Drag 'GR Year' into the 'X-axis' position under the 'Visualizations' tab
3. Next drag both 'GR Male' and 'GR Female' into the 'Y-Axis' position. These will automatically populate as Count. Click on the down arrow. Here you can change the aggregate function from count to median
4. Then drag the 'GR Label (grouping)' column the 'Filters' tab. Make sure to put it in the 'Filters on this visual' section
5. Hover over the column you just dragged over. Click the down arrow. Select the box next to 'Median Earnings'
6. In the 'Visualizations' tab there are three icons. Click on the icon that looks like a magnifying glass
7. Expand the 'Error bars' selection. Turn on the 'Options' section. Then select either the Male of Female column
8. Then turn on the 'Error band' and turn off the 'Bar' option
9. Under the 'Options' section turn on 'Make symmetrical'. Then drag the 'GR (Male or Female) Margin of Error' to the upper bound section
10. Repeat the error bar section for the other gender

**Formating the Visual**

1. Under the 'Visualizations' section click the middle icon. It has a paint brush
2. Expand the 'X-axis' row then the 'Title' row. Make the title text 'Year'
3. Expand the 'Y-axis' row then the 'Title' row. Make the title text 'Median Salary'
4. Move to the 'General' tab
5. Expand the 'Title' row then the 'Title' row again. Make the text 'Median Salary for Female and Male'
6. Make the background color '#F0A787' and turn on the 'Divider'
7. Expand the 'Effects' Row and the 'Visual border' row.
8. Turn on the border and change the 'Rounded corners' to 10 px.
9. Turn on the shadow

Congratulations!! You have officially recreated a Power BI visual. 
