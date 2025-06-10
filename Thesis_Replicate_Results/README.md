## Folder 1: Thesis_Replicate_Results
### Thesis methodology scripts and example data

In this folder, the R script files and data have been presented to allow the user to replicate the results in the order they have been presented in the content of the Thesis. The first file that needs to be run, as indicated below, loads the corresponding functions and generates processed files for each chapter's analysis. The next two files correspond to the analysis results displayed for the ‘toy example’ used to illustrate the Methdology steps in Chapter IV. The next file reads in the example case transcripts and replicates the results as displayed for the single full case analysis in Chapter V. Finally, the last file presents the code to analyze the multiple example cases transcripts and replicate the visualization panels.  

### How to run the code?
First open and run the ThesisGeneralPipeline.Rmd file. This file contains the functions necessary to carry out procedures for cleaning, pre-processing, generating sentiment scores, extraction of PMI transformation matrices, and the calculation of dot product values for every example transcript analyzed in different sections of the Thesis. The files are then saved in the same folder to be read in each chapter’s corresponding analysis script.

#### a) General Processing
File name: *ThesisGeneralPipeline.Rmd* 
Includes cleaning, pre-processing, sentiment scoring, PMI transformation and dp calculator functions. Generates and saves the files required for each chapter’s analysis.

After the complete script for this file has been succesfully loaded, proceed to open and run the remaining files in the order they are presented below, to replicate the results for each corresponding chapter.

#### b) Chapter IV. Methodology 
File name: *ChapterIV_toy_example_part1.Rmd*
The R Markdown script ChapterIV_toy_example_part1.Rmd runs the toy example analysis for the Dr. Beck and Abe short excerpt of the transcript for session 2, used to illustrate each step of the process for the first section of Chapter IV.
	
File name: *ChapterIV_toy_example_part2.Rmd*
The R Markdown script ChapterIV_toy_example_part2.Rmd runs the analysis for the full example transcript for the case of Dr. Beck and Abe sessions 2 and 10 to illustrate the three-layered methodology application process for each level. It includes the visualization output displayed in this chapter of the thesis.
	
#### c) Chapter V. Example Case
File name: *ChapterV_Example_Case.Rmd*
Loads the files for client 1 analysis and generates the results for the application of all three levels as displayed in Chapter V.

#### d) Chapter VI. Multiple Cases
File name: *ChapterVI_Multiple_Case_Comparison.Rmd*
Loads the generated files for multiple clients and generates the panel plots for each level analysis results.
