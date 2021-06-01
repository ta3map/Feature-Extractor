# Feature-Extractor
Manually pinpoint objects and put them into group. To configure the categories and features you want to pinpoint, change the [corresponding tables](#settings). Look at the sample dataset to bring your data to the analyzable format.

[Download link](https://disk.yandex.ru/d/QNL7aZe7rltaDg)
# Measurements
Select the object that interests you. Here, for example, is the face of a monkey. If the image name already has a category name, you don't need to select a category.
![GitHub Logo](/screenshots/screen1.png)
Select the features. Here, we denote that it is a monkey. Secondly, we note that it is a face of a monkey. We don't mark it as a baby, because it's an adult monkey.
![GitHub Logo](/screenshots/screen2.png)

## Add Object
To add an object, click "Add Object". It will appear in the results table. Here in the table, features are saved - this is a monkey, this is a face, this is an adult monkey. Also marked here is the area that this selection occupies (Area) and the total area of the entire image (Image area). These last columns are always present in the table.
![GitHub Logo](/screenshots/screen3.png)

## Delete object
If you added an object by mistake and want to delete it, click "Delete object". To switch between objects, use " + - " buttons.
![GitHub Logo](/screenshots/screen4.png)
## Next picture/Previous
Use "Next picture" and "Previous" buttons to switch between images.
![GitHub Logo](/screenshots/screen6.png)
## Save Results
After you have marked and described all the objects in the pictures, you can save the results to a csv table by clicking on the "Save Results" button.
![GitHub Logo](/screenshots/screen5.png)

## Show table in folder
To see where the analysis results are located, click "Show table in Folder".
![GitHub Logo](/screenshots/screen7.png)
## New Table
To make a new measurement, click "New Table". A new empty table will appear.
![GitHub Logo](/screenshots/screen8.png)

# Settings
In the "Settings" tab, paths to the initial data are marked. The first line is the path to the folder with all images you are interested in. For example, in this case, we use pictures from the example.
![GitHub Logo](/screenshots/screen9.png)
## Category table 
All possible categories are listed in the categories table (categories.csv).
![GitHub Logo](/screenshots/screen10.png)
## Feature table
All features that could be selected (monkey, face, adult or child) are listed in the first row of the features table (features. csv).
![GitHub Logo](/screenshots/screen11.png)
