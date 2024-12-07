# Final Project Repository

This repository contains the code and revisions for the Final Project developed by **Naomi Buell**, **Alexander Simon**, and **Richie Rivera**. Link to our project presentation: https://docs.google.com/presentation/d/1rlTIdZuWD051CAaSmXPsX9qOsIEkOI7AMN-FFWNHilY/edit?usp=sharing.

## Abstract

Background: Opioid addiction is a public health crisis that has affected countless lives. Medicaid, which is a health insurance program for low-income individuals in the US, plays an important role in helping people with opioid use disorder (OUD) get medical treatment. The Affordable Care Act expanded Medicaid coverage in 2014, but not all states have implemented it yet.
 
Research Question: Is there a correlation between OUD prevalence rates in US states and the status of Medicaid expansion?
 
Methods: We downloaded data on the prevalence of pain reliever misuse in each state from the National Survey on Drug Use and Health from the Substance and Mental Health Services Administration for all available years (2016–2019 and 2022) and the status of each state’s decision on Medicaid expansion from KFF, a health policy organization. Data were cleaned and merged into a Pandas dataframe and visualized with scatter plots, line plots, and choropleth maps created using matplotlib and Plotly Express. We also performed linear regression and a paired t-test for difference in means using Python.
 
Results: Forty states had post-expansion data, 10 had pre-expansion data, and 8 had both pre- and post-expansion data. Overall OUD prevalence rates ranged from 1.3% to 6.5% (mean 3.9%). Choropleth maps showed that OUD prevalence rates have trended downward nationwide from 2016 to 2022. Linear regression analysis suggested that the rate of decline in post-expansion states was slightly faster than in pre-expansion states (slope = -0.24 vs -0.19), but R2 values were low (0.2–0.3). The t test was significant (P=0.048), however, not all test assumptions were met.
 
Conclusion: Our results suggest that there is a correlation between OUD prevalence rates and Medicaid expansion status, and that expansion is associated with a faster decline. However, we did not have enough data points to conclude that the difference is statistically significant.
