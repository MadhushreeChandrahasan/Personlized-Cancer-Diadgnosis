# Personlized-Cancer-Diadgnosis

Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/

Data: Memorial Sloan Kettering Cancer Center (MSKCC)

Download training_variants.zip and training_text.zip from Kaggle.

# Context:
Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/discussion/35336#198462

# Problem statement :
Classify the given genetic variations/mutations based on evidence from text-based clinical literature.

# Data Overview
Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/data
We have two data files: one conatins the information about the genetic mutations and the other contains the clinical evidence (text) that human experts/pathologists use to classify the genetic mutations.
Both these data files are have a common column called ID
Data file's information:

training_variants (ID , Gene, Variations, Class)
training_text (ID, Text)
Posing as ML Problem
        There are nine different classes a genetic mutation can be classified into => Multi class classification problem   
