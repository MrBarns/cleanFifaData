# FIFA '21 Data Cleaning Challenge
This is the documentation of my participation in Promise Chinonso's **Data Cleaning Challenge**. The dataset used for this challenge contains information on player ratings in FIFA '21.

The goal of the project is to make the dataset suitable for analysis, the exact nature of which was unspecified. Therefore, my goal was to achieve a dataset with accurate information that would be relevant to a wide range of analyses.

## Technologies
* This project's development environment is Jupyter Notebook.
* The scripts are written in the Python programming language
## Approach
My approach to the challenge is as follows:
* Inspection and Planning
* Cleaning
### Inspection and Planning
__Inspection__ involved visually inspecting each column to determine what information it was trying to display, whether said information was relevant and what format it should be displayed in.

__Planning__ then involved deciding how best to transform the column from what is was to what it should be based on the results of the inspection. As the inspection for most of the columns was perfunctory, the output of the planning phase was not meant to be followed strictly. Rather it was meant to serve as a guide on what to expect as I went from column to column.
## Project Files and Folders

|Name|Description|
|---|---|
|Raw|Contains versions of the raw dataset. v2 was cleaned in this case
|Working_on|Contains instances of the dataset as saved during the cleaning process|
|Worked_on|Contains the final cleaned version of the dataset
|CleaningDates.ipynb|It mostly works on columns carrying date related values 
|CleanMoney.ipynb|It mostly works on columns describing monetary values
|CleanPosition.ipynb|This mostly works on columns related to a player's role on the pitch|
|CleanStats.ipynb|It mostly works on columns relating to a player's attribute statistics
|Coleslaw.ipynb|This defines the coleslaw function for convenient use throughout the cleaning process
|DataCleaning.ipynb|This is the beginning of the cleaning process proper
|Inspect_Strategize.ipynb|This details the process of inspecting the database and developing a strategy for the curation process.
