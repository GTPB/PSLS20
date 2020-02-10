# Multiple regression tutorial

On the fourth day of the "Practical Statistics for the Life Sciences (2020)" course, we will have three exercises multiple regression, based on different datasets:

#### 1) The fish tank dataset

In this experiments 96 fish (dojofish, goldfish and zebrafish) were placed separately in a tank with two liters of water and
a certain dose (in mg) of a certain poison EI-43,064. The resistance of the fish a against the poison was measured as the
amount of minutes the fish survived upon adding the poison (Surv_time, in minutes). Additionally, the weightt of each fish was
measured.

Yesterday, we have seen that with a simple linear regression model we are several variables that influence the association
between the survival time of the fish and the poison dosage. By using a multiple linear regression model, we will learn 
how to account for this.

- Exercise: [exercise_1](./08-MultipleRegression_fish_half.html)
- Data: "https://raw.githubusercontent.com/GTPB/PSLS20/master/data/poison.csv"
- Solution: 

#### 2) The FEV dataset

The FEV, which is an acronym for forced expiratory volume, is a measure of how much air a person can exhale during  a forced 
breath. In this dataset, the FEV of 606 children, between the ages of 6 and 17, were measured. The dataset also provides 
additional information on  these children: their `age`, their `height`, their `gender` and, most importantly, whether the 
child is a smoker or a non-smoker.

The goal of this experiment was to find out whether or not smoking has an effect on the FEV of children.

Yesterday, we already touched upon how the observed effect between smoking and the FEV in a simple linear regression
model could be confounded with the other variables in the dataset. By using a multiple linear regression model, we will learn 
how to account for this.

- Exercise: [Exercise_2](./08-MultipleRegression_FEV_half.html)
- Data: "https://raw.githubusercontent.com/GTPB/PSLS20/master/data/fev.txt"
- Solution

#### 3) The KPNA2 dataset

- Exercise: [exercise_3](./08-multipleRegression_KPNA2_half.html)
- Data: "https://raw.githubusercontent.com/GTPB/PSLS20/master/data/kpna2.txt"
- Solution: [Solution_3](./08-multipleRegression_KPNA2.html)













