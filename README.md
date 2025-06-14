## psychotherapy-NLP-methodology

### Thesis R code for replication of the results and general application of the NLP methodology for psychotherapy analysis

The following repository presents an outline of the code implemented in the thesis project Natural Language Processing (NLP) techniques as methodology for psychotherapeutic treatment research, which has been construed as to allow the user to either replicate the analysis as it is presented in this project, or use it to analyze their own dataset. For replication of the results, the code has been presented in the order they are displayed on the thesis.

Folders:
#### 1) Thesis_Replicate_Results
Thesis methodology scripts and example data:

This folder contains the R files and example data needed to run through the analysis for each Chapter displaying results from the application of the methodology (including the toy example from the methodology description in Chapter IV, the single full example case analysis in Chapter V, and the multiple case analysis in Chapter VI.


#### 2) Thesis_Methodology_Functions
Three-layered methodology functions for external application:

This folder includes the R files with the functions and a description on how to apply the three-layered methodological framework on an external dataset. Important to note is that previous to the pre-processing function, the research may be required to manually re-adapt the cleaning function to fit their raw textual data, since each textual data source may differ on the type of characters and phrases that need to be removed to return the appropriate format for subsequent analysis in the pre-processing functions.
