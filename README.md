# Data_Fairness_Project

## Project 1 Description
In 2016, ProPublica published an analysis of the Correctional Offender Management Profiling for Alternative Sanctions (COMPAS) tool. COMPAS is a proprietary tool which generates a so-called risk assessment for defendants in a criminal trial. ProPublica's analysis focused on the "recidivism score," which purports to provide the likelihood of recidivism (i.e. committing a misdemeanor of felony) within two years of assessment.

## Project 1 Outline
1. Import the data, implement a few pre-processing steps, and inspect the data
2. Run a short exploratory analysis of the COMPAS recidivism score, our primary variable of interest
3. Reproduce the logistic regression model in ProPublica's analysis and interpret the estimates
4. Compute the predictive accuracy of the risk score labels

## Project 2 (Detecting and Mitigating Biases using Fairlearn) Description
We will use the ACS PUMS files, particularly a fraction of the ACS Income dataset, and train a classifier to predict whether an individual has a salary greater than $50K. The protected attribute will be the sex of the individual.

## Project 2 Outline
1. Load the dataset and conduct basic data exploration and preprocessing
2. Explore possible fairness metrics
3. Train a logistic regression classifier and evaluate the fairness of this classifier
4. Train other logistic regression classifiers with pre-processing interventions and re-evaluate fairness
5. Compare the results obtained in 3 and 4

## Project 3 (Deeply Mitigating Bias Using Fairlearn) Description
We will continue working on the same data and ML model, this time using Fairlearn to perform bias-mitigating interventions in three different way.

## Project 3 Outline
1. Load the data as we did in Project 2
2. Use preprocessing algorithms to mitigate bias
3. Use reduction algorithms to mitigate bias
4. Use postprocessing algorithms to mitigate bias
5. Compare all of our efforts
