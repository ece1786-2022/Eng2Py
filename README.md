# Eng2Py
Welcome to the "Eng2Py" Project Repo, please follow the descriptions below for each file

## Data files
All files in .txt format are Data files used for generating the Training, Validation and Testing splits including the raw files in the "Data Files" folder

## Notebook - Datasets.ipynb
This file is to load the Data splits in .csv formats for further use in the model notebooks

## Notebook - Eng2Py_t5_pretrain_1.ipynb
This file was used to explore the capabilities of the Original T5 model, all other model notoebooks are based on the code in this file

## Notebook - codet5_small_baseline.ipynb
This file in contains our baseline model, which was to do the baseline comparisons

## Notebook - codet5_base_without_fine_tuning.ipynb
This file in contains the original codet5 model (base variant without finetuning) used to report if the pre-trained model itself produces good results

## Notebook - codet5_base_finetuned_on_sorting.ipynb
This notebook contains the main model of our project, the fine-tuned model parameters saved in the local folder (exceeds the limit of Github file size) were used in the hand-labelling notebooks.

## Notebook - Hand_Labelling_Dhairya.ipynb & Hand_Labelling_Yuchen.ipynb
These notebooks display the individual evaluations of our model on the testing set

(Please note that the notebooks use google drive as the space to save some files hence please change the arguments for paths to successfully run the notebooks)
