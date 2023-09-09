# Parkinsons-Disease-Detection
DESCRIPTION - Parkinson’s disease is a neurological disorder with more than 6 million people worldwide suffering from it.It is commonly diagnosed using clinical assessments and progression scale which usually depends on the medical practitioner’s expertise ,and accuracy varies greatly between various examiners which also takes a long time to accurately diagnose.
This project proposes to develop a computer aided diagnostic method to diagnose Parkinsons Disease patients using MRI images of the brain ,which in turn reduces cross examiner variability and the time required to diagnose.


DATASET - This dataset is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD). Each column in the table is a particular voice measure, and each row corresponds to one of 195 voice recordings from these individuals ("name" column). The main aim of the data is to discriminate healthy people from those with PD, according to the "status" column which is set to 0 for healthy and 1 for Parkinson's Disease.

**Attribute Information:**

**Matrix column entries (attributes):**

**name** - ASCII subject name and recording number

**MDVP:Fo(Hz)** - Average vocal fundamental frequency

**MDVP:Fhi(Hz**) - Maximum vocal fundamental frequency

**MDVP:Flo(Hz)** - Minimum vocal fundamental frequency

**MDVP:Jitter(%) , MDVP:Jitter(Abs) , MDVP:RAP , MDVP:PPQ , Jitter:DDP** - Several measures of variation in fundamental frequency

**MDVP:Shimmer , MDVP:Shimmer(dB) , Shimmer:APQ3 , Shimmer:APQ5 , MDVP:APQ , Shimmer:DDA** - Several measures of variation in amplitude

**NHR , HNR** - Two measures of ratio of noise to tonal components in the voice

**status** - Health status of the subject (one) - Parkinson's, (zero) - healthy

**RPDE , D2** - Two nonlinear dynamical complexity measures

**DFA**- Signal fractal scaling exponent

**spread1 , spread2 , PPE** - Three nonlinear measures of fundamental frequency variation


APPROACH - To build an effective supervised classification model using Support Vector Machine algorithm, K - Nearest Neighbour algorithm and Random Forest algorithm.


OUTPUT - The accuracy of the model is around 87%.

TECHNOLOGY USED - Python, Machine Learning

![image](https://github.com/divyanshsahu2020/Parkinsons-Disease-Detection/assets/80671629/766739f5-9381-42c3-87a6-3e0191897f36)
