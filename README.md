# Statistical Learning in Epidemiology Project

This repository contains the final project developed for the course 'Statistical Learning in Epidemiology'. The project focuses on applying survival analysis methods to data from the AIDS Clinical Trials Group (ACTG) Study 175 a pivotal clinical trial evaluating the effectiveness of antiretroviral treatments in HIV-positive individuals. It provides an excellent opportunity to explore how modern data analysis techniques can contribute to understanding patient outcomes.

### Overview
- Dataset: ACTG Study 175 – UCI Machine Learning Repository
- Project Notebook
- README

### Dataset

The dataset is sourced from the UCI Machine Learning Repository and is based on data published in 1996. It includes comprehensive clinical, demographic, and categorical information on 2,139 HIV-1 positive patients enrolled in a randomized, double-blind clinical trial.

- Study Design: Randomized, double-blind trial with a 2-year follow-up period

- Population: 2,139 HIV-positive individuals, all previously treated with zidovudine (AZT)

- Features: 23 baseline variables including CD4 count, Karnofsky score, gender, weight, age, and others

- Objective: To assess the effectiveness of combination therapy versus monotherapy in slowing or preventing the progression to AIDS

Participants were randomly assigned to one of four treatment groups: Zidovudine (AZT) alone, AZT + Didanosine (ddI), AZT + Zalcitabine (ddC), Didanosine (ddI) alone

### Project Summary

Scientific Questions Addressed:

- Which variables influence the progression of AIDS?

- Do combination treatments offer superior protection against disease progression?

- Among the four regimens, which treatment yields the most favorable survival outcomes?

This analysis employs survival analysis techniques, ideal for handling censored data where the event of interest (such as death or disease progression) may not have occurred for all individuals within the study period.

The analytical workflow includes:

- Data Cleaning and Exploration: Preliminary inspection, handling of missing values, and examination of variable distributions across treatment groups.

- Kaplan-Meier Estimation: Non-parametric estimation of survival functions for each treatment group and comparison via log-rank tests.

- Cox Proportional Hazards Model: Multivariate modeling to identify significant predictors of disease progression, estimate hazard ratios, and test the proportional hazards assumption.

- Model Interpretation and Validation: Interpretation of covariate effects, visualization of adjusted survival curves, and diagnostic checks to validate model assumptions.

### Conclusion

This project demonstrates the power of statistical learning techniques especially survival analysis in epidemiological research. The findings offer not only predictive insights into the progression of HIV, but also support evidence-based clinical decision-making. Emphasizing interpretability and real-world impact, this project highlights the relevance of modern data science in public health and medicine.

