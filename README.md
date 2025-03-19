# hw2_Rcode
BCB Homework 2

The file hw2_Gates.Rmd is the R markdown file that contains all code and necessary references with comments.

The code is meant to produce multiple different directories such as raw_data and processed_data where raw_data has copies of the fang_et_al_genotypes and the snp_positions data. The proccessed_data will contain directories maize_data and teosinte_data where all output files from maize and teosinte will go to their respective folders. Processed_data will also contain the 3 graphs produced from Part 2 of the assignement.

You will notice that in this github repository these directories that were made for clarity sake are actually missing. This is because when I was trying to "commit" from R, there were some erorrs that I could not solve. This forced me to upload files individually thus not allowing me to show the actual output of my .Rmd. I opted to upload only the output files and the hw2_Gates.Rmd

This code works with a couple assumptions:
1) you have tidryr and readr installed, if not you can run the following in the hw2_Gates.Rmd --> install.packages(c("tidyr", "readr"))
2) fang_et_al_genotypes.txt and snp_positions should be located in your base directory
   - You will not have to make copies or make new directories (ie raw_data or processed_data) prior to running the code, the code will do it for you
3) hw2_Gates.Rmd is in your base directory
  
Goals of the Code:
1) Create raw_data repository that holds copies of the raw data fang_et_al_genotypes.txt and snp_positions.txt
2) Create processed_data thats hold folders for maize_data and teosinte_data to help organize output files. Any ouput from the code should go into processed data.
3) Effectivly sort and clean raw data for appropriate formatting and groups names
4) Creates 40 files for maize and teosinte in ascending and descending order based on "?" and "-"
5) Produces 3 different graphs that visualizes comparisons

Please let me know how I can improve anything for clarity or how to make the code better. Thank you!
