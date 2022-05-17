# GIRFT_Covid19_NosocomialInfections
Identification of Covid-19 nosocomial infections in English hospitals using machine learning

## Background
COVID-19 nosocomial infections (NIs) may have played a significant role in the dynamics of the pandemic in England, but analysis of their impact at the national scale has been lacking. Our aim was to provide a comprehensive account of NIs, identify their characteristics and outcomes in patients with a diagnosis of COVID-19 and use machine learning modelling to refine these estimates.

## Methods
From the Hospital Episodes Statistics database all adult hospital patients in England with a diagnosis of COVID-19 and discharged between March 1st 2020 and March 31st 2021 were identified. A cohort of suspected COVID-19 NIs was identified using four empirical methods linked to hospital coding. A random forest classifier was designed to model the relationship between acquiring NIs and the covariates: patient characteristics, comorbidities, frailty, trust capacity strain and severity of COVID-19 infections.

## Findings
In total, 374,244 adult patients with COVID-19 were discharged during the study period. The four empirical methods identified 29,896 (8.0%) patients with NIs. The random forest classifier estimated a mean NI rate of 10.5%, with a peak close to 18% during the first wave, but much lower rates thereafter and around 7% in early spring 2021. NIs were highly correlated with longer lengths of stay, high trust capacity strain, greater age and a higher degree of patient frailty. NIs were also found to be associated with higher mortality rates and more severe COVID-19 sequelae, including pneumonia, kidney disease and sepsis.

## Interpretation
Identification of the characteristics of patients who acquire NIs should help trusts to identify those most at risk. The evolution of the NI rate over time may reflect the impact of changes in hospital management practices and vaccination efforts. Variations in NI rates across trusts may partly reflect different data recording and coding practice.
