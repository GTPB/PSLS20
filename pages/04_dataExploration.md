In the first day of the "Practical Statistics for the Life Sciences (2020)" course, we will have four tutorials on data exploration, based on different datasets:

1) The NHANES dataset:

The National Health and Nutrition Examination Survey (NHANES) contains data that has been collected since 1960. 
For this tutorial, we will make use of the data that was collected  between 2009 and  2012, for 10.000 U.S. civilians. 
The dataset contains a large number of physical, demographic, nutritional and life-style-related parameters.

Getting familiar with the dataset will always be the first step in a data analysis pipeline.
In this tutorial, you will learn the key principles of data exploration in R, including data import, tidying, wrangling and visualisation. 

- Exercise: [https://raw.githubusercontent.com/GTPB/PSLS20/master/tutorialScripts/excercises/04_DataExploration/Data_exploration_NHANES.Rmd](https://raw.githubusercontent.com/GTPB/PSLS20/master/tutorialScripts/excercises/04_DataExploration/Data_exploration_NHANES.Rmd)
- Data: "https://raw.githubusercontent.com/GTPB/PSLS20/master/data/NHANES.csv"

2) The armpit dataset:

Smelly armpits are not caused by sweat, itself. The smell is caused by specific micro-organisms belonging to the group of
Corynebacterium spp. that metabolise sweat. Another group of abundant bacteria are the Staphylococcus spp.,
which do not metabolise sweat in smelly compounds.

The CMET-groep at Ghent University does research on transplanting the armpit microbiome to help people with smelly armpits.
To test the effect of transplanting the microbiome, they conducted an experiment on two groups of volunteers: one group was
treated with a placebo, while the other had a microbiome transplant. The goal was to find whether or not the relative abundance 
Staphylococcus spp.  in the microbiome of the armpit is significantly  different between subjects treated with the placebo 
and subjects treated with a microbial transplant.

In this tutorial, you will use your acquired skills from exercise 1 to explore the armpit dataset all by yourself!

- Exercise: [https://raw.githubusercontent.com/GTPB/PSLS20/master/tutorialScripts/excercises/04_DataExploration/Data_exploration_armpit.Rmd](https://raw.githubusercontent.com/GTPB/PSLS20/master/tutorialScripts/excercises/04_DataExploration/Data_exploration_armpit.Rmd)
- Data: "https://raw.githubusercontent.com/GTPB/PSLS20/master/data/armpit.csv"


3) The captopril dataset:

The captopril dataset holds information on a small experiment with 15 patients that have increased blood pressure values. 
More specifically, for each patient we will have four values; one value for systolic blood pressure and one for diastolyic,
both before and after treating the patient with a drug named captopril.

In this tutorial on data exploration, you will learn how to deal with data from paired experimental designs.

- Exercise: [https://raw.githubusercontent.com/GTPB/PSLS20/master/tutorialScripts/excercises/04_DataExploration/Data_exploration_captopril.Rmd](https://raw.githubusercontent.com/GTPB/PSLS20/master/tutorialScripts/excercises/04_DataExploration/Data_exploration_captopril.Rmd)
- Data: "https://raw.githubusercontent.com/GTPB/PSLS20/master/data/captopril.txt"

4) The FEV dataset:

The FEV, which is an acronym for forced expiratory volume, is a measure of how much air a person can exhale (in liters)  during  a forced breath. 
In this dataset, the FEV of 606 children, between the ages of 6 and 17, were measured. The dataset also provides additional information on 
these children: their `age`, their `height`, their `gender` and, most importantly, whether the child is a smoker or a non-smoker.
The goal of this experiment was to find out whether or not smoking has an effect on the FEV of children.

In this tutorial, you will learn about the importance of confounders in real-life datasets.


- Exercise: [https://raw.githubusercontent.com/GTPB/PSLS20/master/tutorialScripts/excercises/04_DataExploration/Data_exploration_FEV.Rmd](https://raw.githubusercontent.com/GTPB/PSLS20/master/tutorialScripts/excercises/04_DataExploration/Data_exploration_FEV.Rmd)
- Data: "https://raw.githubusercontent.com/GTPB/PSLS20/master/data/fev.txt"




