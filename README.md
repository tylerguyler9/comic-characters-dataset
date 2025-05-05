# comic-characters-dataset
Data research project on the traits of comic characters

# Project Overview
Here's a summary of this research project
## Dataset
* This project makes use of [two datasets found on Kaggle](https://www.kaggle.com/datasets/fivethirtyeight/fivethirtyeight-comic-characters-dataset)
  * `dc-wikia-data` and `marvel-wikia-data`
* This project creates a new dataset containing both the DC and Marvel characters
  - `comic_characters` which can be found [here](src/data/comic_characters.csv)
## Questions
* How common are each eye color, hair color, and sex?
* Which comic characters appear the most?
## Research / Visualizations
* [Most Common Eye Colors of Comic Characters](src/visualizations/Most_Common_Eye_Colors_of_Comic_Characters.png)
* [Most Common Hair Colors of Comic Characters](src/visualizations/Most_Common_Hair_Colors_of_Comic_Characters.png)
* [Sexes of Comic Characters](src/visualizations/Sexes_of_Comic_Characters.png)
* [Comic Characters With Most Appearanes](src/visualizations/Comic_Characters_With_Most_Appearanes.png)

These were created using [research.ipynb](src/research.ipynb)
# Conclusions
* The most common eye colors of the comic characters are: blue, brown, green, black, and red
* The most common hair colors of the comic characters are: black, brown, blond, red, and "no"
* There are more male comic characters than female comic characters (4699 males, 2316 females)
* The comic characters with the most appearances are: Batman, Superman, Green Lantern, James Gordon, and Richard Grayson
# Limitations
 * Not all entries had complete information, so a lot of comic characters were excluded from the dataset (the clean dataset has 7,281 names but the original dataset has 23,272 names)
# Future Work
 * Look into the first appearance year of each character
