# Bone Modifying Agents and Outcomes in Patients with Metastatic Castration-Sensitive Prostate Cancer Treated with Abiraterone Acetate

This repository contains the R code used in the study "Bone-Modifying Agents in Patients With High-Risk Metastatic Castration-Sensitive Prostate Cancer Treated With Abiraterone Acetate". The study was published in JAMA Network Open: https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2816217

In this study, we analyzed the effect of bone modifying agents (BMAs) on outcomes in patients with metastatic castration-sensitive prostate cancer (mCSPC) treated with abiraterone acetate, based on the individual participant-level data from the LATITUDE trial.

The results of the LATITUDE trial were previously published: https://www.nejm.org/doi/full/10.1056/NEJMoa1704174

We found evidence that the use of BMAs was associated with a longer time to skeletal-related events (SREs) in patients with mCSPC treated with abiraterone acetate plus androgen deprivation therapy (ADT). Furthermore, we also found that BMAs were associated with longer overall survival and time to SREs in patients treated with placebo plus ADT.

## Repository contents

| File | Description |
|---|---|
| `analysis_all_patient_cohort.R` | Main analysis in the full cohort (R) |
| `analysis_subgroup_cohort.R` | Subgroup analysis (R) |
| `rmstd_aap.R` | Restricted mean survival time difference, abiraterone acetate plus ADT arm (R) |
| `rmstd_adt.R` | Restricted mean survival time difference, placebo plus ADT arm (R) |

## Requirements

R (version 4.x) with the following packages: `cobalt`, `gdata`, `ggsci`, `gtsummary`, `haven`, `lubridate`, `missForest`, `pec`, `RISCA`, `smd`, `survival`, `survminer`, `tidyverse`, `WeightIt`.

## Data availability

This repository contains analysis code only. The patient-level data analysed in the study are not distributed here.

## License

The code in this repository is released under the [MIT License](LICENSE).
