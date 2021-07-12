# Transcriptome-Analysis
This repository contains R markdown files and input datasets for the transcriptomic analysis of Rhodoluna lacicola and Aurantimicrobium sp. strain MWH-Mo1

# Notes
Input data files are included in this repository. 
Running these analyses requires R.

# Files
There are three .Rmd files for the bioinformatic analysis of *R.lacicola* and *Aurantimiccrobium* sp. strain MWH-Mo1 light/dark cycling RNA-Seq data:

1. **timeseries_transcriptome_analysis.Rmd**<br/>
  This code is for the DSEQ2 and hierarchical clustering analyses and related plots.<br/>
  
  The input files for this analysis are:<br/>
  >
    1a. ta8_raw_counts_formatted.txt
    1b. ta8_rc_formated_col_conditions.txt
    1c. raw_count_formated.txt
    1d. raw_count_formated_col_conditions.txt

2. **GO_Term_Distribution_Plot.Rmd**<br/>
  This code is for the GO-slim term distribution analysis and related plots.<br/>
  
  The input files for this analysis are:<br/>
  >
    2a. Ta8_go_slim_count.txt
    2b. Mo1_go_slim_count.txt
    
3. **Fisher_Test_Analysis.Rmd**<br/>
  This code is for the odds ratio calculation and related plots of the merged hierarchically clustered gene groups.<br/>
  
  The input files are:<br/>
  >
    3a. Ta8_Macro_Groups_Fischer_Test_Data.csv
    3b. Mo1_Macro_Groups_Fischer_Test_Data.csv
