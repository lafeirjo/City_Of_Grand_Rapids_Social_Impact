## City of Grand Rapids Install Instructions

**For installing anaconda**
1. The following instructions are available through the anaconda documentation site. Click on the link below and follow the instructions for your specific device. [Anaconda Install](https://docs.anaconda.com/free/anaconda/install/index.html)

**For setting up the Jupyter Notebook Environment**
1. With Anaconda, clone the City of Grand Rapids GitHub using the following link:    [GitHub Repository](https://github.com/lafeirjo/City_Of_Grand_Rapids_Social_Impact/tree/main)

   a. When going to clone the directory, it is easiest to copy it right onto your desktop for easy access in future steps.
   
   b. Once you are in the desktop, copy and paste the code below to clone our repository to the directory you changed to.
   
         git clone https://github.com/lafeirjo/City_Of_Grand_Rapids_Social_Impact.git
   
   c. Once your repository is cloned, run the command below to move you into the directory that you just cloned.

         cd "City_Of_Grand_Rapids_Social_Impact

2. Retrieving all the demo code data:

   a. Moving away from the command line, you want to start by navigating to the actual folder cloned onto the desktop. Navigate into 'Install_Instructions' -> 'Demo_Code'

   b. Next, we shift to the teams folder, where in the 'Datasets' folder, you will find a folder called 'Demo_Code_Data'. Copy this folder and paste it into the 'Demo_Code' folder in the repository.

   c. Finally, take the 'DemoCode.ipynb' file and move that into the 'Demo_Code_Data' folder.
         
   
4. Setting up the correct environment.

   a. Paste the following code below into your conda environment

         conda env create --prefix ./envs --file environment.yml
   
   b. Once the terminal finishes processing the above command, paste the below code

         conda activate ./envs

5. After the environment finishes setting up, copy and paste the following cell to open a JupyterLab tab

        Jupyter Notebook

7. You will be taken to the Jupyter Notebook screen, which will open in your browser, displaying all the files in your environment.

8. From here you can access the demo code directory by:

   a. Click on ‘Install_Instructions’.

   b. Click on ‘Demo_Code’.

   c. Click on 'Demo_Code_Data'

   d. Open the 'DemoCode.ipynb' file, which you can now run with all correct installations and data files.
   
**For Setting up PowerBI**
The following set of instructions have been grabbed from the official Microsoft store website: 
[Power BI Install](https://learn.microsoft.com/en-us/power-bi/fundamentals/desktop-getting-started)

1. To download Power BI Desktop, go to the Power BI Desktop download page (linked above) and select Download Free. Or for download options, select See download or language options. You can also download Power BI Desktop from the Power BI service. Select the Download icon in the top menu bar, and then select Power BI Desktop.

2. On the Microsoft Store page, select Get, and follow the prompts to install Power BI Desktop on your computer. Start Power BI Desktop from the Windows Start menu or from the icon in the Windows taskbar. The first time Power BI Desktop starts, it displays the Welcome screen.

3. From the Welcome screen, you can Get data, see Recent sources, open recent reports, Open other reports, or select other links. Select the close icon to close the Welcome screen.

4. Along the left side of Power BI Desktop are icons for the three Power BI Desktop views: Report, Data, and Model, from top to bottom. The current view is indicated by the yellow bar along the left, and you can change views by selecting any of the icons.

5. If you're using keyboard navigation, press Ctrl + F6 to move focus to that section of buttons in the window. To learn more about accessibility and Power BI, visit our accessibility articles.

6. Power BI Desktop also includes the Power Query Editor, which opens in a separate window. In Power Query Editor, you can build queries and transform data, then load the refined data model into Power BI Desktop to create reports.

**Opening up our demo PowerBI dashboard**
1. Navigate back to our demo code folder. If you have already exited out of the jupyter notebook from before, please follow steps 1 through 3 under "For setting up the Jupyter Notebook Environment." This will get you back to our Demo repository.

   a. Click on ‘Demo_Code’

   b. Click on the square box to the left of Grand_Rapids_Health_Dashboard.pbix. This will highlight that line and put a check mark in the box that you clicked.

   c. Now that this file is highlighted click the box in the upper left corner that says "Download." This will download our PowerBI to your local device.

   d. Since you have already downloaded PowerBI to your device, you can navigate to where our demo PowerBI dashboard downloaded on your local device. Click on our PowerBI dashboard "Grand_Rapids_Health_Dashboard.pbix" This will open the dashboard in PowerBI on your local device. 

**Next Steps**   
1. Now that the install instructions are done, the next step in the process is reproducibility, which the instructions for can be found here: [Reproducibility Instructions](https://github.com/lafeirjo/City_Of_Grand_Rapids_Social_Impact/blob/main/Install_Instructions/Reproducibility.md)
