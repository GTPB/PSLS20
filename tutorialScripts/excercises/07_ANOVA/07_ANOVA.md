On the third day of the "Practical Statistics for the Life Sciences (2020)" course, we will have three tutorials on ANOVA, based on different datasets:

1) The  lettuce freshweight dataset

In agricultere, it is important to have a high yield of crops. One way to increase the number of leaves (or better, total leaf weigth) 
is by using a fertilizer.  

Here, we consider three types of fertilizers:
- biochar
- compost
- cobc (combination of biochar and compost)

The researchers want to find out if either of these fertilizers have a positive influence
on the growth of lettuce plants. To this end, they grew up lettuce plants in a greenhouse. The pots were filled with
one of four soil types;

- Soil only (control)
- Soil supplemented with biochar (refoak)
- Soil supplemented with compost (compost)
- Soil supplemented with both biochar and compost (cobc)

The dataset `freshweight_lettuce.txt` contains the freshweight for 28 lettuce plants. 
The researchers want to test if  there is an effect of one or more of the treatments on the growth of lettuce plants.

- Exercise: ["https://raw.githubusercontent.com/GTPB/PSLS20/master/tutorialScripts/excercises/07_ANOVA/ANOVA_lettuce_plants_half.Rmd"]("https://raw.githubusercontent.com/GTPB/PSLS20/master/tutorialScripts/excercises/07_ANOVA/ANOVA_lettuce_plants_half.Rmd")
- Data: "https://raw.githubusercontent.com/GTPB/PSLS20/master/data/freshweight_lettuce.txt"


2) The cuckoo dataset 

The common cuckoo does not build its own nest: it prefers to lay its eggs in another birds' nest. It is known, since 1892,
that the type of cuckoo bird eggs are different between different locations. In a study from 1940, it was shown that cuckoos return
to the same nesting area each year, and that they always pick the same bird species to be a "foster parent" for their eggs.

Over the years, this has lead to the development of geographically determined subspecies of cuckoos. These subspecies have evolved in
such a way that their eggs look as similar as possible as those of their foster parents.

The cuckoo dataset contains information on 120 Cuckoo eggs, obtained from randomly selected "foster" nests.
The researchers want to test if the type of foster parent has an effect on the average length of the cuckoo eggs. 

- Exercise: ["https://raw.githubusercontent.com/GTPB/PSLS20/master/tutorialScripts/excercises/07_ANOVA/ANOVA_cuckoo_half.Rmd"]("https://raw.githubusercontent.com/GTPB/PSLS20/master/tutorialScripts/excercises/07_ANOVA/ANOVA_cuckoo_half.Rmd")
- Data: "https://raw.githubusercontent.com/GTPB/PSLS20/master/data/Cuckoo.txt"



3) The NHANES dataset:

The National Health and Nutrition Examination Survey (NHANES) contains data that has been collected since 1960. 
For this tutorial, we will make use of the data that was collected  between 2009 and  2012, for 10.000 U.S. civilians. 
The dataset contains a large number of physical, demographic, nutritional and life-style-related parameters.

We want to test whether or not the mean systolic blood pressure value (take column `BPSys1`) is equal between the five self-reported
health categories. To this end, we will use an ANOVA analysis (if the required assumptions are met).

- Exercise: [https://raw.githubusercontent.com/GTPB/PSLS20/master/tutorialScripts/excercises/07_ANOVA/ANOVA_NHANES_half.Rmd](https://raw.githubusercontent.com/GTPB/PSLS20/master/tutorialScripts/excercises/07_ANOVA/ANOVA_NHANES_half.Rmd)
- Data: "https://raw.githubusercontent.com/GTPB/PSLS20/master/data/NHANES.csv"


