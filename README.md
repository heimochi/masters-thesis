This repository contains the analysis and modeling scripts for my Master’s thesis.

The project investigates brain-behavior relationships using neuroimaging and behavioral data from the ABCD Study.

# XGBoosting the Signal: A Machine Learning Approach for Informant-Sensitive Predictions of OCD Symptoms in Children Based on Brain Morphology

**Author:** Margrete Soya Heimvik  
**Supervisors:** Øystein Sørensen, Ina Drabløs  
**Institution:** Centre for Lifespan Changes in Brain and Cognition (LCBC), University of Oslo  

Data used in this thesis is sourced from the ABCD Data Release 5.1 (Haist & Jernigan, 2023).

Note: Access to raw data requires proper credentials through the NIMH Data Archive (NDA).

## Project Overview

This thesis explores whether machine learning applied to structural brain imaging can predict obsessive-compulsive symptoms in children, and how predictions vary depending on the reporting informant (child vs. parent). Using data from the **Adolescent Brain Cognitive Development (ABCD) study**, XGBoost classifiers were trained to predict internalizing symptom severity from parcellated brain volume features.

---

## Research Questions

1. Can structural MRI features predict the severity of OCD-related internalizing symptoms in children?
2. Does predictive accuracy differ between child- and parent-reported symptoms?

---

## Methods

- **Dataset:** ABCD study (via LCBC collaboration)  
- **Input:** Parcellated sMRI brain volume features  
- **Targets:**  
  - Parent-reported: Child Behavior Checklist (CBCL)  
  - Child-reported: Brief Problem Monitor (BPM)  
- **Model:** XGBoost (with matched preprocessing, class balancing, and tuning)  
- **Evaluation:** ROC, precision, recall, permutation testing

## Key Findings

- Models achieved high accuracy, but performance was largely due to class imbalance.
- Neither child- nor parent-report models significantly outperformed chance.
- Slight advantage in ROC for child-report model did not translate into better classification.
- Structural brain features alone were not predictive of OCD-related symptoms.


## Conclusion

The study suggests that sMRI-derived structural features have limited value in predicting internalizing OCD symptoms in children. Results highlight the challenges of low symptom prevalence, informant discrepancies, and the need for multimodal approaches in pediatric neuropsychiatric research.

## Disclaimer

This was my first full coding project, and the code reflects a learning process.

Scripts may be repetitive or messy in places. I've prioritized functionality over elegance while trying to improve along the way.
