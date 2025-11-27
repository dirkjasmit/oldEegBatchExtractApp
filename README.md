# EegBatchExtractApp

A MATLAB appdesigner gui to perfrom EEG parameter extraction in batch mode.

## Explanation of the procedure

1. Select the cleaned files you need to extract the parameters from
2. Select a file with all the availbale channels and without any additional channels. channel location info is the only data that will be used.
3. <optional> indicate whether missing channels need to be imputed. Channel not in the refernce file (impute file) will be removed (e.g. EOG channels)
4. indicate the frequency band to analyze (only for some extraction parameters, like DFA, band power)
5. select the EEG parameter to extract
6. click batch. The command line output will indicate where the data are stored (usually in global variables)
7. Access these variables with >> global <varname>

