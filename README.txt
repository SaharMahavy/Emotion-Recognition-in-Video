Hello!

This README file is here in order to prevent any confusions regarding the content of the .zip folder in the submission of this project, and to make sure it is run appropriately.

The .zip folder contains the "Final Project" folder which contains:
1. A Jupyter Notebook file named "Emotion-Recognition.ipynb".
2. A data folder containing two other folders- "videos" and "labels":
- "labels" contains 18 .csv files with the labels to the 18 .mp4 files in "videos"
3. A folder named "outputs" containing .mp4 videos produced in the making of the project-
 As you will see, there are commented parts in the notebook. Running some of those made some runtime issues and RAM crashes, and in order to prevent those when reviewing the project, we decided to run them "offline" and provide them in the folder.
 All of the videos in the outputs folder were made using the "create_timeline_plot" function that is coded in the notebook.
 

The project was written completely within "Google Colab", so the default base path of the project is set accordingly, and the "drive.mount" function was in use.
Changing the "base_path" variable placed in the 4th cell of the notebook should work as long as the hierarchy of the files remains.
The correct hierarchy is:
Any working directory should contain the notebook itself aswell as the data and outputs folders. The "base_path" variable should be changed to the name of this directory.
For example, for this hierarchy:

E:/
├───another_project
├───some_project
└───the_best_project!
    ├───data
    │   ├───labels
    │   └───videos
    ├───outputs
	└───Emotion-Recognition.ipynb
	
base_path should be "E:/the_best_project!/"


Hope you will enjoy reviewing our project!

Nir, Ron, Sahar and Omri.