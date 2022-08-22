# YFT Review Questions

The overarching reason for this YFT assessment review is the question:

**Why was the 2020 assessment more optimistic than the previous assessment?**

```
A. Comparing 2017 and 2020 assessment
B. Selectivity
C. Growth
D. Maximum age
E. Tags
F. Regions
G. New MFCL features
H. Natural mortality
I. Data collection
J. CPUE
K. Model complexity
L. Uncertainty
M. Diagnostics
N. Summary plots and tables
```

---

### A. Comparing 2017 and 2020 assessment

1. The 2020 assessment estimates a more optimistic stock status than the 2017
   assessment. Is this because of a larger numerator (SB), smaller denominator
   (SBF=0, dynamic B0), or both?

2. The 2020 assessment estimates a more optimistic stock status than the 2017
   assessment. Is this because of changes in recruitment, M, maturity, body
   weights, F, or dynamic B0 between the two assessments?

3. Of all the changes between the 2017 and 2020 assessments, which ones had the
   greatest effect on the estimated stock status?

### B. Selectivity

1. Which fisheries, if any, should be grouped in terms of selectivity?

2. Should one longline fishery within each region have a non-decreasing
   selectivity?

3. Should selectivity be modelled using cubic splines or parametric curves?

4. Selectivity can only be modelled as age-based in MFCL, is this problematic
   for the YFT assessment?

5. Are the fits to the purse seine length compositions adequate, or can
   selectivity be improved for the purse seine?

### C. Growth

1. Should the growth curve be estimated internally in the assessment model or
   externally?

2. Should lengths from tagging data be included when fitting an external growth
   model?

3. Should the growth follow a parametric von Bertalanffy curve, a nonparametric
   curve, or in between (e.g., first 8 ages nonparametric)?

4. Should other growth curves be considered as alternatives to von Bertalanffy?

5. Should the external von Bertalanffy growth curve model be fitted to otoliths
   only or tagging data plus otoliths? Results from both analyses are available,
   presented in 2020.

### D. Maximum age

1. What is an appropriate maximum age in the YFT assessment?

### E. Tags

1. Should the tag mixing period be 2 quarters or tag release group specific (as
   done in the SKJ 2022 assessment)?

2. Is the tagging data informative about migrations, mortality, and/or stock
   size?

3. Could the tag-related plots and tables in the assessment report be improved?

### F. Regions

1. Is it worth considering a simpler regional structure, e.g., a 4-region model
   which might capture the main dynamics of the YFT fishery and have better
   statistical properties of estimability?

2. What should be the basis of regional boundaries? Aspects to consider,
   including biology, fishery, management, model parsimony, model convergence,
   estimability, ease of diagnostics, ease of interpretation?

### G. New MFCL features

1. Should fishing mortality be estimated using a catch-errors or
   catch-conditioning approach?

2. Should recruitment be estimated using an orthogonal-polynomial approach?

3. In addition to the Dirichlet-multinomial approach to weight length
   compositions, should the uncertainty grid include arbitrary sample size
   scalars?

### H. Natural mortality

1. Review the approach used to determine M at age and implications of
   alternative M assumptions. Could tagging data be informative for estimating
   M?

2. What shape would be appropriate when estimating M at age from life history
   parameters?

3. What effect did the change in M have on depletion?

### I. Data collection

1. Are there gaps in the data collection that could be improved in the sampling
   programme?

2. What fisheries and regions should be sampled for future close-kin
   mark-recapture data collection?

### J. CPUE

1. Should effort creep be included in the CPUE data and what is the best way to
   do that?

2. Can the VAST analysis from 2020 of yellowfin longline CPUE data be improved
   for the next assessment?

3. Should multiple CPUE indices be considered?

4. Should additional process error be added to the CPUE index, e.g., using a
   loess smoother and/or estimating an additional standard error?

5. Should CPUE catchability ungrouped or grouped between regions, enabling
   regional scaling?

### K. Model complexity

1. Is the level of model complexity appropriate, including spatial and fishery
   structure, in relation to data inputs and other available information.

2. Are the patterns of high recruitment in temperate regions and low recruitment
   in region 8 (near Papua New Guinea) in agreement with the available data, or
   can the model be simplified to reduce the possibility of model balancing
   unrelated to data?

### L. Uncertainty

1. Is there a better way to represent uncertainty about management quantities,
   combining structural and estimation uncertainty?

2. What model runs should be included in the structural uncertainty grid, as
   opposed to one-off sensitivities, and how should they be weighted?

3. If the estimation uncertainty about depletion is very small, evaluated using
   the delta method or likelihood profile, what other approaches could be used
   to evaluate the estimation uncertainty?

### M. Diagnostics

1. Which standard stock assessment plots would be useful but are not provided in
   the assessment report?

2. Which diagnostics would be useful but are not provided in the assessment
   report?

3. How should model convergence be addressed in the assessment report, criteria
   such as jittering of initial parameter values, parameters on bounds, final
   gradients, positive definite Hessian, parameter correlations, etc.

4. Is there consistency between input and output variances for the CPUE, length
   compositions, and tag recaptures?

5. Diagnose possible problems fitting the data in Fishery 18, Indonesian
   handline in Region 7. Is the observed catch in tonnes higher than the
   estimated exploitable biomass, and is the fishing mortality hitting a
   parameter bound at 1.3?

### N. Summary plots and tables

1. Data: Total length comps over time (bubble plot or 3d histograms)

2. Data: Median length over time, with confidence limits and possibly overlaid
   with (Results) a line showing median length in the model population?

3. Results: Population numbers at age as a table and/or bubble plot?

4. Results: Also plot CPUE by year instead of quarters?

---

### Comments/questions for the SAM team:

Now:

- Was M changed at the CondAge step in the 2020 model development?

Later:

- Add a diagnostic to the data inputs report, identifying tag release groups
  that have recapture rates lower than a given threshold.

- Add a table/plot showing tag releases and recoveries by 9x9 region.

---

### Sources for additional questions

Summary Report from 2020

Matt's powerpoint (YFT work plan.pptx)

Matt's text file (WorkingPlan.txt)
