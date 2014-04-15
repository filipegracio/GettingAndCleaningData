# this file describes the purpose of run_analysis.R and the output files produced by running said script.


the file run_analysis.R takes the data from the UCIHAR Dataset and processes it (details below). The files needs to changed such that the "yourPath" variable specifices where the UCIHAR Dataset variables have been downloaded to. The path specification system is consistent with linux operating systems. 

run_analysis.R works by reading in the files from test and training sets, loading in variable names and appropriately name the R variables' columns and rows. The Test and Train datasets are merged into a singl matrix of  (observations) x (variables), where each observation is one of the 10299 data points captured in the appropriate study[1], and each of the rows is one of the variables measured. The script proceeds to creating a reduced version of the dataset where only "means" of the 3D data are included in the "reduced" version of the dataset. 


For details see description of the appropriate file xMatrixRecuced.csv in the codebook.md file. 
2) Produce a new dataset, newData.csv, which contains only the average value of each of the variables for each subject. For details see the description of the appropriate file newData.csv in the codebook.md file.
