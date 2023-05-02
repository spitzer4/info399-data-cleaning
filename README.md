# info399-data-cleaning
INFO 399 Data Cleaning Research Project

Research completed under Bertram Ludaescher during my senior year of undergraduate studies at the University of Illinois at Urbana-Champaign.

## Table of Contents
- [Introduction](#introduction)
- [Data](#data)
- [Jupyter Notebook](#jupyter-notebook)
- [Research Report](#research-report)
- [Open Refine Files](#open-refine-files)
- [Usage](#usage)

## Introduction
Restaurant inspections are conducted by the Food Protection Division of the Chicago Department of Public Health (CDPH). This ensures that food served to the public at licensed food establishments follows food safety guidelines. Inspections are performed on retail food establishments such as restaurants, grocery stores, hospitals, convenience stores, and schools. The inspections focus primarily on food handling practices, product temperatures, personal hygiene, facility maintenance, and pest control. 
Data with reference to inspections that have taken place in the Chicago area have been compiled into the dataset ‘Food_Inspections.csv’. The data was collected by the City of Chicago Department of Health. The data includes inspection date, results, violations noted, business name, latitude and longitude location, license number, and risk. The dates covered are 01/02/2013 to 08/28/2017.

## Data
Data can be found in the 'data' folder or on [Kaggle](https://www.kaggle.com/datasets/chicago/chi-restaurant-inspections). The 'data' folder includes datasets representing several iterations of data cleaning.

## Jupyter Notebook
The Jupyter notebook located at 'Analysis.ipynb' contains code for analyzing and visualizing the Food Inspections data. The pandas and matplotlib libraries are used to examine how the proportion of passing Facility Types changes over time for each Facility Type.

## Research Report
The research report located at 'Report.pdf' contains a high level overview of the research project. This includes a project description, process overview, cleaning steps taken, and evaluation of results. 

## Open Refine Files
I have included the 'history.json' and 'Food-Inspections-v2.openrefine.tar.gz' files. The 'history.json' file contains the history of data transformations applied to 'Food_Inspections.csv'. 'Food-Inspections-v2.openrefine.tar.gz' is a compressed file that contains the OpenRefine project files. This can be useful for reproducing the data transformations and cleaning steps performed in the project.

## Usage
1. Clone the repository to your local machine.

    ```git clone https://github.com/spitzer4/info399-data-cleaning.git```

2. Navigate to the repository directory.

    ```cd your_repository```

3. Install the required dependencies.

    ```pip install pandas matplotlib```

4. Open the 'Analysis.ipynb' Jupyter Notebook file.
5. Run the cells in the notebook to reproduce the analysis.



