# Fetal health classification model using Supervised Machine Learning.
## The task
###### Modelling and correct prediction of fetal health can be effectively used to prevent child and maternal mortality.

## The data
The dataset used is available for free in Kaggle(Uploaded by andrewmvd).
Find the dataset here https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification.
This dataset contains 2126 records of features extracted from Cardiotocogram exams, which were then classified by three expert obstetritians into 3 classes:
1. Normal
2. Suspect
3. Pathological


#### What kind of data can we get from Cardiotocogram exams
Taken from https://patient.info/pregnancy/cardiotocography: Cardiotocography (CTG) measures your baby's **heart rate**. At the same time it also monitors the **contractions in the womb (uterus)**. CTG is used both before birth (antenatally) and during labour, to monitor the baby for any signs of distress. By looking at various different aspects of the baby's heart rate, doctors and midwives can see how the baby is coping.

#### Columns
1. 'baseline value'- FHR baseline (beats per minute)
2. 'accelerations'- Number of accelerations per second
3. 'fetal_movement'- Number of fetal movements per second
4. 'uterine_contractions'- Number of uterine contractions per second
5. 'light_decelerations'- Number of light decelerations per second
6. 'severe_decelerations'- Number of severe decelerations per second
7. 'prolongued_decelerations'- Number of prolonged decelerations per second
8. 'abnormal_short_term_variability'- Percentage of time with abnormal short term variability
9. 'mean_value_of_short_term_variability'- Mean value of short term variability
10. 'percentage_of_time_with_abnormal_long_term_variability'- Percentage of time with abnormal long term variability
11. 'mean_value_of_long_term_variability'- Mean value of long term variability
12. 'histogram_width'- Width of FHR histogram
13. 'histogram_min'- Minimum (low frequency) of FHR histogram
14. 'histogram_max'- Maximum (high frequency) of FHR histogram
15. 'histogram_number_of_peaks'- Number of histogram peaks
16. 'histogram_number_of_zeroes'- Number of histogram zeros
17. 'histogram_mode'- Histogram mode
18. 'histogram_mean'- Histogram mean
19. 'histogram_median'- Histogram median
20. 'histogram_variance'- Histogram variance
21. 'histogram_tendency'- Histogram tendency



Files included
  1. Folder containing dataset
  2. File containing initial examination and visualisation of data
  3. File containing the model code.
