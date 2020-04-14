# Data Merging and Cleaning for Capstone Project 1
This directory has an IPython notebook which merges the datasets of the CSV files (International Medical Devices Database download link: https://medicaldevices.icij.org/p/download) used in this project and cleans the final dataset, in terms of fixing missing values, deleting unuseful columns, and modifying existing columns. The output file (df_final.csv) obtained by running the Capstone Project 1 Dataset - Final-Edited.ipynb notebook can be used for exploring the data and later for modeling. The data wrangling and cleaning document details the methods and steps taken to merge the datasets and clean the final dataset.

devices-1562662526.csv - This file contains data concerning the devices reported.

manufacturers-1562662522.csv - This file contains data concerning the manufacturers of the devices reported.

events-1562662544.csv - This file contains data pertaining to the events the reported devices were involved in.

df_final.csv - This file contains the dataset merged from devices-1562662526.csv, manufacturers-1562662522.csv, and events-1562662544.csv and cleaned for data exploration and analysis for the project
