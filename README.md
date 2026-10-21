# Bone-modifying agents in metastatic castration-sensitive prostate cancer treated with abiraterone acetate

R code for the analysis reported in:

> Bone-Modifying Agents in Patients With High-Risk Metastatic Castration-Sensitive Prostate Cancer Treated With Abiraterone Acetate. *JAMA Network Open*. <https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2816217>

Post hoc analysis of individual participant data from the LATITUDE trial, comparing time to skeletal-related events and overall survival between patients who did and did not receive bone-modifying agents.

## Contents

- `analysis_all_patient_cohort.R`: main analysis, full cohort
- `analysis_subgroup_cohort.R`: subgroup analysis
- `rmstd_aap.R`: restricted mean survival time difference, abiraterone acetate arm
- `rmstd_adt.R`: restricted mean survival time difference, placebo arm

## Requirements

R 4.x with `cobalt`, `gdata`, `ggsci`, `gtsummary`, `haven`, `lubridate`, `missForest`, `pec`, `RISCA`, `smd`, `survival`, `survminer`, `tidyverse`, `WeightIt`.

## Data

Patient-level data are not included in this repository.

## License

[MIT](LICENSE)
