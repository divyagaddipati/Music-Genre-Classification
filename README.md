# Music-Genre-Classification

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Dataset](#dataset)
  * [Technologies](#technologies)
  * [Installation](#installation)
* [Contact](#contact)
* [Sources](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project
Develop a model that can accurately classify tracks to a genre in order to improve song recommendation systems.

<!-- DATASET -->
## Data Set
Dataset used for the project can be found in the below link:

<a href="https://drive.google.com/drive/folders/1EeiLUBJm5C5_YrhfQ5GTBsbePDi2bmho?usp=sharing">FMA: A Dataset For Music Analysis Data Set</a>

<br />
The dataset we used is “FMA: A Dataset For Music Analysis Data Set” from the UCI Machine Learning Repository. The dataset contains 106,574 music tracks (instances), and 518 features. The set of features for each instance include things like ID, title, artist, genres, tags, and play counts.

<br />

<!-- TECHNOLOGIES -->
## Technologies
* Sklearn
* Pandas, Numpy 

<!-- INSTALLATION -->
### Installation
```
cd Music-Genre-Classification
pip install -r requirements.txt
jupyter notebook
```

Order to run python notebooks in:

1. Preprocessing_Part1 - initial preprocessing of data from website
2. Data Augmentation - data augmentation conducted on initially preprocessed data to add ~110,000 instances
    - Approximately 10 hours
3. Preprocessing_Part2 - final preprocessing of the initial data and the augmented data
4. Models_and_Analysis_milestone - training and evaluation of models on a subset of the dataset
5. Models and Analysis - modeling and analysis on the full dataset

*Training models takes significant amount of time*

<!-- CONTACT -->
## Contact
Argyro Major            argyrock@vt.edu

Divya Gaddipati         divyaj@vt.edu

Conrad Pereira          conradpereira@vt.edu

<!-- SOURCES -->

### Sources

[1] Defferrard, M., Benzi, K., Vandergheynst, P., & Bresson, X. (2017, May 24). FMA: A Dataset 
For Music Analysis Data Set. UCI Machine Learning Repository. Retrieved October 19, 
2021, from 
https://archive.ics.uci.edu/ml/datasets/FMA%3A+A+Dataset+For+Music+Analysis. 
https://github.com/mdeff/fma

[2] Ma, E. (2019, June 4). Data Augmentation for Audio. Medium. Retrieved October 19, 2021, 
from https://medium.com/@makcedward/data-augmentation-for-audio-76912b01fdf6. 

[3] Schedl, M., Zamani, H., Chen, C.-W., Deldjoo, Y., & Elahi, M. (2018, April 5). Current 
challenges and visions in Music Recommender Systems Research. International Journal 
of Multimedia Information Retrieval. Retrieved October 19, 2021, from 
https://link.springer.com/article/10.1007/s13735-018-0154-2. 
