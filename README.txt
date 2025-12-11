manybabies_merged.csv is the main dataset containing all habituation trials. A separate data file, manybabies_merged_data_dictionary.pdf, is provided to explain every variable in manybabies_merged.csv.

manybabies_merged.csv was created by homogenizing and merging data from the ManyBabies 1, 3, and 4 projects. The full processing pipeline, including all cleaning, harmonization, and merging steps, is documented in ManyBabies Data Processing.qmd. A less detailed overview of this whole process is given with ManyBabies Data Processing Overview.pdf. 

The Original Data Files folder contains the unmodified source datasets (MB1, MB3, MB4). When ManyBabies Data Processing.qmd is executed, it reads these original files and produces the merged output file manybabies_merged.csv.

ManyBabies Data Processing.html is the rendered HTML output generated from ManyBabies Data Processing.qmd. 

manybabies_validation.xlsx contains a manual validation check performed after merging. For each original dataset (MB1, MB3, MB4), 10 participants were sampled, and we verified whether they appeared correctly in the merged file. If participants didn't show up in the merged file, we checked whether exclusion was due to the appropriate criteria. 

