# Non-parametric analysis tutorial

On the third/fourth day of the "Practical Statistics for the Life Sciences (2020)" course, we will have one exercise on non-parametric analysis for two groups
and one exercise for non-parametric analysis for multiple groups.

#### 1) The Shrimps dataset:

PCBs are often present in coolants, and are know to accumulate easily in the adipose tissue of shrimps. In this experiment, two
groups of 18 samples (each 100 grams) of shrimps each were cultivated in different conditions, one control condition and one condition 
where the medium was polluted with PCBs. 

The research question is; is there an effect of the  growth condition on the PCB concentration in the adipose tissue of shrimps?

- Exercise: [Exercise_1](https://raw.githubusercontent.com/GTPB/PSLS20/master/tutorialScripts/excercises/05_statisticalInference/Hypothesis_testing_shrimps_half.Rmd)
- Data: "https://raw.githubusercontent.com/GTPB/PSLS20/master/data/shrimps.txt"
- Solution: [Solution_1](./05-Non_parametric_shrimps.html)

#### 2) The lettuce freshweight dataset

In agriculture, it is important to have a high yield of crops. One way to increase the number of leaves (or better, total leaf weight) 
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

- Exercise: ["Exercise_2"](./Kruskal_Wallis_lettuce_plants_half.html)
- Data: "https://raw.githubusercontent.com/GTPB/PSLS20/master/data/freshweight_lettuce.txt"
- Solution: [Solution_2](./Kruskal_Wallis_lettuce_plants.html)


