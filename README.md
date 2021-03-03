# A Dungeon Master's Guide to Clustering
Created by Aidan Whelan for the IU Machine Learning For All Club  
3 March 2021  

## Overview  
This hands-on workshop sits at the intersection of classic machine learning techniques and Dungeons & Dragons, the classic tabletop roleplaying game that's celebrated by generations.  
Participants will be guided through the elegant and powerful K-means algorithm as they cluster fantasy monsters by their in-game attributes. With a provided Juputer notebook and skeleton code, participants will use tools such as Pandas, NumPy, Matplotlib, and Seaborn for interactive, multidimensional visualizations.

## Requirements  
This workshop is intended to be used with Python 3.  

The packages used in this workshop are:  
- Matplotlib (graphing and plotting back-end)
- NumPy (mathematical utilities)
- Pandas (dataframe/input file handling)
- Seaborn (interactive graphing and plotting front-end)

To install these packages, please use the provided requirements file with the following command in your shell:  
`pip3 install -r requirements.txt`

## Instructions  
In this directory, there are four files:  

### monsters.csv  
This file contains the data that will be used as the input to our clustering algorithm. You will not need to change this file.  
The file was acquired from the Kaggle dataset "Dungeons & Dragons: a collection of data about Dungeons & Dragons" published by user **shadowtime2000** on 2 August 2020. The full dataset, including data on heroic classes, equipment, character races, and spells for 5th edition Dungeons & Dragons can be found [here](https://www.kaggle.com/shadowtime2000/dungeons-dragons).  

### requirements.txt  
This file contains information on the Python packages required to run this workshop. Please run this as recommended above before proceeding.  

### dm_clustering_BASE.ipynb  
This file contains the provided skeleton code from which workshop attendees will conduct their experiments. The skeleton code includes code that is necessary but not the subject of this workshop. If you are an **attendee**, please open and edit this file.  

### dm_clustering_REF.ipynb  
This file contains the complete version of the code from which the workshop may be led. For the purposes of this workshop, this file should not be changed. If you are a **workshop leader**, please open this file and use it as a reference.  
