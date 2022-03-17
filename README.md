# false_peaks_experiments
The data, analysis, and outputs of the paper "False Peaks: On the Estimation of Fuzzing Effectiveness" submitted to ESEC/FSE 2022.


### Notebooks
Analysis of data and outputs generation was done within the "analysis.ipynb" R script. 
It can be found in the directory ./scripts 

### Data
Our datasets are massive (i.e. hundrads of GBs). 

For making data sharing possible, we provide the R workspaces (i.e. .Rda or .Rdata files)  that can easily be loaded when running the analysis.ipynb script. 

Please note that you have to set REGENERATE_DATA =FALSE all times as we load the required data from above mentioned R workspaces.

Important: Please unzip/extract the data from "fuzz_data.zip" file before running the notebook.

### Figures
All the figures are saved to ./figures directory
