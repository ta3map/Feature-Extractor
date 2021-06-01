# Feature-Extractor
Manually pinpoint objects and put them  in a table with features. To configure the categories and features you want to pinpoint, change the [corresponding tables](#category-table). Look at the [sample dataset](/Example/) to bring your data to the analyzable format.

[Download link](https://disk.yandex.ru/d/QNL7aZe7rltaDg)
# Measurements
Select the object that interests you. Here, for example, is the face of a monkey. 
![GitHub Logo](/screenshots/screen1.png)
Next, you can select the category.
But if the image name already has a category name in it, you don't need to select anything.

Select the features. Here we indicate that the object belongs to a monkey.

- [x] monkey ~~(other animal)~~

Secondly, we mark the object as a face. 

- [x] face ~~(non-face)~~

We don't mark it as a baby, because it's an adult monkey.

- [ ] ~~baby~~ (adult)

![GitHub Logo](/screenshots/screen2.png)

## Add object
To add an object, click `Add Object`. It will appear in the results table. Here in the table, features are saved - this is a monkey *(monkey = 1)*, this is a face *(face = 1)*, this is an adult monkey *(baby = 0)*. Also the area of this selection is calculated *(Area)* and the total area of the entire image *(Image area)*. These last columns are always in the table.
![GitHub Logo](/screenshots/screen3.png)

## Delete object
If you added an object by mistake and want to delete it, click `Delete object`. To switch between objects, use ` + - ` buttons.
![GitHub Logo](/screenshots/screen4.png)
## Next picture/Previous
Use `Next picture` and `Previous` buttons to switch between images.
![GitHub Logo](/screenshots/screen6.png)
## Save results
After you have marked and described all the objects in the pictures, you can save the results to a csv table by clicking on the `Save Results` button.
![GitHub Logo](/screenshots/screen5.png)

## Show table in folder
To see where the analysis results are located, click `Show table in Folder`.
![GitHub Logo](/screenshots/screen7.png)
## New table
To make a new measurement, click `New Table`. A new empty table will appear.
![GitHub Logo](/screenshots/screen8.png)

# Settings
In the `Settings` tab, paths to the initial data are marked. The first line is the path to the folder with all images you are interested in. For example, in this case, we use pictures from the example.
![GitHub Logo](/screenshots/screen9.png)
## Category table 
All possible categories are listed in the category table *(categories.csv)*.
![GitHub Logo](/screenshots/screen10.png)
## Feature table
All features that could be selected *(monkey, face, adult or child)* are listed in the first row of the feature table *(features.csv)*.
![GitHub Logo](/screenshots/screen11.png)
