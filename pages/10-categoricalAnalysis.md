# Categorical analysis tutorial

On the fifth day of the "Practical Statistics for the Life Sciences (2020)" course, we will have two exercises on categorical analysis:

#### 1) The sore throat example

The "sore" dataset contains results of a study on throat soreness upon surgery with general anaesthesia.  
The variable sore encodes whether a patient experienced a sore throat on waking (0: no, 1: yes),  as a function of the duration of the surgery
(duration) in minutes and the type of device (variable type) used to secure the airway.
Two types of devices were included: aryngeal mask ("mask") or tracheal tube ("tube") (Data taken from Agresti 2002).

- Exercise: [Exercise_1](./10-categorical_sore_half.html)
- Data: "https://raw.githubusercontent.com/GTPB/PSLS20/master/data/sore.csv"
- Solution: [Solution_1](./10-categorical_soreBase.html)
- Extensive solution: [Solution_1_ext](./10-categorical_soreExtended.html)

#### 2) The Salk dataset

In 1916, the US experienced the first large epidemic of polio. John Salk developed a vaccine with promising results in the lab in the early fifties.
In this experiment, children are assigned at random to the control (placebo treatment) or vaccine treatment arm after consent was given by
the parents.

As such, we have two treatment arms
- Control: vaccination with placebo
- Treatment: vaccination with vaccine

In order to limit confounding, the experiment used  double blinding:
- The parents did not know if their child was vaccinated or received the placebo
- The care-giver/researchers did not know if the child was vaccinated or received placebo

After one year, the polio status of the child was recorded. The goal of the experiment is to find out if the vaccine reduces the
incidence of getting the polio disease.

- Exercise: [Exercise_2](./10-salk_half.html)
- Data: The data is generated in the script itself



