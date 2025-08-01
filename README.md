# bayesian_R
This analysis is part of a larger Bayesian modeling project examining cognitive aging in offspring of centenarians versus controls, using data from longitudinal studies conducted at Boston University. The primary outcome is the Telephone Interview for Cognitive Status (TICS) score, measured across five visits.

My contribution focuses on assessing the robustness of the main longitudinal models to missing data in the Age variables (Age02–Age05), which were used to compute time since baseline. Participants with missing age data were excluded from the original analysis (complete-case). To test the sensitivity of the results to this exclusion, I performed mean imputation, replacing each missing Age value with the average Age at that visit across all subjects.

Using this imputed dataset, I re-estimated:

Model 1: Random intercept and slope model with linear time

Model 2: Random intercept model with quadratic time

This sensitivity analysis allows us to evaluate whether model estimates and interpretations remain consistent when imputed data are used instead of excluding observations with missing age.
