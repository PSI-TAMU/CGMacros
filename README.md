# CGMacros: a scientific dataset for personalized nutrition and diet monitoring
![Alt text](photo_cgm_met.svg)

## Overview 
This dataset is primarily designed to predict meal macronutrients using wearable sensors. It contains data from two continuous glucose monitors (CGM) for 45 participants (15 healthy,
16 pre-diabetes, 14 T2D) who consumed meals with varying and known macronutrient compositions in a free-living setting for
ten consecutive days. It also contains multimodal information from an activity tracker, food macronutrients, and food photographs, as well as anonymized participant demographics, anthropometric measurements, and health parameters from blood analyses and gut microbiome profiles. 

## Installation
Install dependencies
```
conda create --name CGMacros 
conda activate CGMacros
pip install -r requirements.txt
```

## Download
The dataset is under review in Physionet. We will update this link once the dataset has been reviewed.

## Folder structure
The dataset is divided into separate folders for each participant (CGMacros-#). Each folder contains a CGMacros-#.csv file which contains the glucose response from two devices, activity, heart rate information from a FitBit for each timestamp as well as macros and the associated meal photos.

## Supplementary files
The dataset also contains the following supplementary files:
1. bio.csv contains anthropometric measurements of each individual, as well as measures of glucose, lipid, insulin derived from blood draw.
2. microbes.csv contains information of the microbes present in the gut microbiome of each subject. The microbes are encoded as 0/1 where, 1 represents the microbe is 
present while 0 means the microbe is not present in that subject.
3. gut health test.csv contains 22 measures of the gut health status reported by Viome. Each feature is represented as 0/1/2 where 0 represents not optimal, 1 represents average, and 2 represents good.
4. parse_data.ipynb contains code to predict iAUC and AUC using anthropometric variables, macronutrients, measures of glucose, lipids, insulin and their associated SHAP plots

## Please note
Participants 24, 25, 37, and 40 did not complete the study and are missing from the dataaset
