# MitoDietAD

Considering the probabilistic expectations of Alzheimer’s disease development or
progression due to specific risk factors or biomarkers we designed a Bayesian model
to formulate the impact of diet-induced obesity with an impaired mitochondrial
function and altered behavior. The applied probabilities are based on clinical trials
globally and are continuously subject to updating and redefinition.
Therefore, the proposed model and the programming code are adjustable to different
parameters and values. The program is coded and executed in Python and is fully and
freely available for research purposes and testing the correlation of diet type and AD
progression regarding various risk factors and biomarkers. The proposed
multiparametric model combines various data types based on uniform probabilities.
The program simulates all the variables with a uniform distribution in a sample of
1000 patients. First, the program initializes age (30-95) and the four different diet
types (‘HFO_diet’, ‘Starvation’, ‘HL_diet’, ‘CR’) along with the factors that are
related to prodromal or mixed AD (ATP, MFN1, MFN2, DRP1, FIS1, Diabetes,
Oxidative_Stress, Hypertension, Obesity, Depression, and Physical_activity).
Then, the program executes the simulation according to the probabilities of Table 1,
assigning value 1 or 0 in the case of a positive or not positive biomarker. The outcome
is a table with the probability of AD development or progression corresponding to a
random individual ID related to diet choices and mitochondrial dynamics parameters.
Besides the known proteins related to mitochondrial dynamics, our model includes
risk factors like Age, Hypertension, Oxidative Stress, Obesity, Depression, and
Physical Activity, which are associated with Prodromal AD.
