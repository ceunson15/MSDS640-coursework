Welcome to the NBA Breakout Project GitHub repository. The goal and purpose of this project is to attempt to accurately predict when NBA players will breakout using player statistics.

The Data folder contains 3 folders for different types of data related to the project. Database folder contains the SQL file to produce a database using the basketball-reference data. The database was originally created in PostgreSQL. The Processed folder contains two csv's with the "Revised_Dataset" containing the updated project dataset and the "GroundTruth_MIP" containing difference values used with the final project notebook. The final folder Raw contains all of the individual 11 NBA season datasets which is provided for transparency.

The Notebooks folder contains all 4 project python notebooks which were originally created and worked on in google colab.

The last folder is the Reports folder which contains the 4 matching reports that pair with their corresponding colab notebook.

In order to reproduce the project results these are the necessary steps to follow:

1) Download the "NBA_Breakout_Final_Notebook.ipynb" from the Notebooks folder, "NBA_Revised_Dataset.csv" and "NBA_GroundTruth_MIP.csv" which both can be found in the Processed folder which is located in the Data folder.

2) Open google colab and select upload notebook to select the "NBA_Breakout_Final_Notebook.ipynb" you just downloaded.

3) Once open on the lefthand side of the screen look for a folder icon called files, click to open and select "upload to session storage".

4) Select the "NBA_Revised_Dataset.csv" and then "NBA_GroundTruth_MIP.csv" that we downloaded from the GitHub earlier.

5) Check the "NBA_Breakout_Requirements.txt" and then install the necessary environment package versions listed here to ensure reproducibility.

6) As long as you have followed every step above you should now be able to successfully recreate the project code for yourself :)

Thank you for reading and interacting with this project!