# AMLS_21-22-_SN17000550
ELEC0134 Applied Machine Learning Systems (AMLS) Final Assignment
Student ID:17000550

Brief Introduction:
This folder/repository contains the files required to run the ELEC0134 AMLS assignment of classifying tumour images and consists of two 
tasks; binary classifier & multiclass classifier. Two datasets, provided by the module organiser, were tested using three classifiers, 
Support Vector Machines (SVM), K-Nearest Neighbours and Decision Trees. Further information on the results and implementation can be found
in the corresponding report.

Organisation and role of files:
This folder consists of 6, including the README file, files required to run the classifiers for the two tasks. A description of the files 
are listed below:
1) README file containing a description and instructions on how to run the project.
2) Task A final code - the final iteration Jupyter Notebook file containing the three classifiers used for Task A (binary task)
3) Task B final code - the final iteration Jupyter Notebook file containing the three classifiers used for Task B (multiclass task)
4) Task A parameter tuning code - this iteration contains codes for loops and plots that were used for classifier's parameter tuning 
purposes
5) Task B parameter tuning code - this iteration contains codes for loops and plots that were used for classifier's parameter tuning 
purposes
6) A screenshot showing an example of what this folder and its content should be for the classifiers to run successfully

Please note that due to size constraints the training and test dataset are not included here and can be found at:
Training dataset: http://shorturl.at/hquDP
Test dataset: https://drive.google.com/file/d/1LS_C_4_iOeqOyEoWPPoksrk8lqdBKagB/view

Additionally before running the Jupyter Notebook files please download the datasets and export the dataset and test folders within the zip 
files to this folder so that the python files can carry out the necessary sorting and preprocessing of the tumour images. A screenshot of 
how this folder should look like before running the codes is provided.

How to run the code: 
- Task A final code and Task B final code are the two main files necessary to run the final classifier models for the project and both 
the codes will run the classifer on the training, validation and test datasets. 
- After downloading and exporting the dataset and test folders into this folder as mentioned above, one can simply open Task A final code 
and Task B final code using Jupyter Notebook and run the cells one by one (There are only 12 cells per Task). 
- Please note that if you are running the code for the first time then enter 'N' in captial when user input is requested.
- For subsequent runs, one can enter 'Y' in capital. Please do this for each file as this runs the necessary code to sort the images into
subfolders and create a dictionary which is used by the rest of the program.

Necessary packages and libraries required:
1) numpy
2) pandas
3) matplotlib.pyplot
4) sklearn
5) skimage
6) os (import os)
7) joblib (import joblib)
8) shutil (import shutil)

The functions and modules imported from within these libraries are included in the Task A final code and Task B final code files.