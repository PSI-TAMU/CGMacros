# CGMacros: a scientific dataset for personalized nutrition and diet monitoring

## Overview 
---
This dataset is primarily designed for predicting meal macronutrients from wearable sensors. It contains continuous glucose monitors (CGM) data for 45 participants (15 healthy,
16 pre-diabetes, 14 T2D) who consumed meals with varying and known macronutrient compositions in a free-living setting for
ten consecutive days. It also contains multimodal information from an activity tracker, two, food
macronutrients, and food photographs, as well as anonymized participant demographics, anthropometric measurements and
health parameters from blood analyses and gut microbiome profiles. 

Please use the Physionet link to access the dataset

The dataset is divided into separate folders for each participant. Each folder contains the glucose response from two devices, activity, heart rate information from a FitBit for each timestamp as well as macros and the associated meal photos.

The dataset also contains the following supplementary files:
bio.csv contains anthropometric measurements of each individual, as well as measures of glucose, lipid, insulin derived from blood draw.


microbes.csv contains information of the microbes present in the gut microbiome of each subject. The microbes are encoded as 0/1 where, 1 represents the microbe is 
present while 0 means the microbe is not present in that subject.

gut health test.csv contains 22 measures of the gut health status reported by Viome. Each feature is represented as 0/1/2 where 0 represents not optimal, 1 represents average, and 2 represents good.

parse_data.ipnb contains code to predict iAUC and AUC using anthropometric variables, macronutrients, measures of glucose, lipids, insulin and their associated SHAP plots


Participants 24, 25, 37, and 40 did not complete the study and are missing 
