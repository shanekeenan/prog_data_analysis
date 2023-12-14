## Assessment repository for Programming for data analysis module

***
Module: Programming for data analysis with lecturer Dr Brian McGinley
Semester 2, Higher Diploma in Science in Data Analytics at ATU, Galway, 2023/24. 

Author: Shane Keenan 

***

## About 

This repository contains two jupyter notebooks for assessment - 

1. project1.jpynb - 

contains code for the first project - Simulating average national house prices in Ireland 
files associated with this work are contained in the data folder namely 
``"data\\project1\\"``


2. project2.jpynb - 

contains code for the second project in this module - An analysis of paleo-present climate data. Description the project tasks are detailed in the "Project 2 - PfDA.pdf" file in the data folder. 

all files assoicated with this project are contained with the data folder under project2. 



## running the code 

Note all data (in both projects) is linked using relative paths to the data folder in the repository. E.g. 
``current_directory = os.getcwd()`` gets the current directory the jupyter notebook is saved and 
``relative_path = "data\\project2\\41586_2008_BFnature06949_MOESM31_ESM.xls"`` defines the relative path from the notebook to the data file. which is then added to the current directory 
``file_path = os.path.join(current_directory, relative_path)``

Therefore if the repository is cloned locally there should be no need to change file names to run the notebook.



steps
1. Install Anaconda 
2. Install visual studio code 
3. create a github account 
4. create public repository "prog_data_analysis" with README.md and .gitignore file
5. Sign into github using VScode 
6. Clone repository to PC 
7. Create necesary notebooks and folders
8. Commit all and push to repo 


## Issues 










***


