# PECO
Data and Matlab notebook files for "Not so smart? 'Smart' drugs increase the level but decrease the quality of cognitive effort "

MATLAB NOTEBOOKS (known to work with Release 2022b)
1. Figures.mlx has code and access to data for figures in main text
2. SOM.mlx has code and access to data for figures and tables in SOM
3. SOM_Cantab.mlx has code and access to data for figures in SOM that combine CANTAB data and knasack data

DATA:
1. Raw data from KNAPSACK TASK are in Xall_figures.csv
2. Raw data from CANTAB TASKS are in files PECO_CANTAB_*.csv
3. Merged data knapsack/cantab tasks are in files Zall*.csv (see SOM_Cantab.mlx for code that merges (1) and (2)); records in these csv files have been re-ordered already so that participant 3 is first (see "Important Note" in mlx notebook SOM_Cantab.mlx)