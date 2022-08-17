# YFT Review Questions

The overarching reason for this YFT assessment review is the question:

**Why was the 2020 assessment more optimistic than the previous assessment?**

**A1.a** Which fisheries, if any, should be grouped in terms of selectivity?

**A1.b** Should one longline fishery within each region have a non-decreasing
         selectivity?

**A1.c** Should selectivity be modelled using cubic splines or parametric
         curves?

**A1.d** Selectivity can only be modelled as age-based in MFCL, is this
         problematic for the YFT assessment?

**A2.a** Should the growth curve be estimated internally in the assessment model
         or externally?

**A2.b** Should lengths from tagging data be included when fitting an external
         growth model?

**A2.c** Should the growth follow a parametric von Bertalanffy curve, a
         nonparametric curve, or in between (e.g., first 8 ages nonparametric)?

**A2.d** Should other growth curves be considered as alternatives to von
         Bertalanffy?

**A3** What is an appropriate maximum age in the YFT assessment?

**A4.a** Should the tag mixing period be 2 quarters or tag release group
         specific (as done in the SKJ 2022 assessment)?

**A4.b** Is the tagging data informative about migrations, mortality, and/or
         stock size?

**A4.c** Could the tag-related plots in the assessment report be improved?

**A5.a** Is it worth considering a simpler regional structure, e.g., a 4-region
         model which might capture the main dynamics of the YFT fishery and have
         better statistical properties of estimability?

**A5.b** What should be the basis of regional boundaries? Aspects to consider,
         including biology, fishery, management, model parsimony, model
         convergence, estimability, ease of diagnostics, ease of interpretation?

**A6.a** Should fishing mortality be estimated using a catch-errors or
         catch-conditioning approach?

**A6.b** Should recruitment be estimated using an orthogonal-polynomial
         approach?

**A6.c** In addition to the Dirichlet-multinomial approach to weight length
         compositions, should the uncertainty grid include arbitrary sample size
         scalars?

**A6.d** A new alternative approach to model movement was trialled in the 2022
         SKJ assessment but the results were not considered plausible. [This is
         a placeholder for discussion].

---

**B1.1** Review the approach used to determine M at age and implications of
         alternative M assumptions.

**B1.2** What shape would be appropriate when estimating M at age from life
         history parameters?

**B1.3** What effect did the change in M have on depletion?

**B2.1** Are there gaps in the data collection that could be improved in the
         sampling programme?

**B2.2** What fisheries and regions should be sampled for future close-kin
         mark-recapture data collection?

**B3.1** Should effort creep be included in the CPUE data and what is the best
         way to do that?

**B3.2** Can the VAST analysis from 2020 of yellowfin longline CPUE data be
         improved for the next assessment?

**B3.3** Should multiple CPUE indices be considered?

**B3.4** Should additional process error be added to the CPUE index, e.g., using
         a loess smoother and/or estimating an additional standard error?

**B3.5** Should CPUE catchability ungrouped or grouped between regions, enabling
         regional scaling?

**B4.1** Is the level of model complexity appropriate, including spatial and
         fishery structure, in relation to data inputs and other available
         information.

**B5.1** Is there a better way to represent uncertainty about management
         quantities, combining structural and estimation uncertainty?

**B5.2** What model runs should be included in the structural uncertainty grid,
         as opposed to one-off sensitivities, and how should they be weighted?

**B5.3** If the estimation uncertainty about depletion is very small, evaluated
         using the delta method or likelihood profile, what other approaches
         could be used to evaluate the estimation uncertainty?

**B6.1** Which standard stock assessment plots would be useful but are not
         provided in the assessment report?

**B6.2** Which diagnostics would be useful but are not provided in the
         assessment report?

**B6.3** How should model convergence be addressed in the assessment report,
         criteria such as jittering of initial parameter values, parameters on
         bounds, final gradients, positive definite Hessian, parameter
         correlations, etc.

**B6.4** Is there consistency between input and output variances for the CPUE,
         length compositions, and tag recaptures?

---

**D1.1** The 2020 assessment estimates a more optimistic stock status than the
         2017 assessment. Is this because of a larger numerator (SB), smaller
         denominator (SBF=0, dynamic B0), or both?

**D1.2** The 2020 assessment estimates a more optimistic stock status than the
         2017 assessment. Is this because of changes in recruitment, M,
         maturity, body weights, F, or dynamic B0 between the two assessments?

**E1.1** Data: Total length comps over time (bubble plot or 3d histograms)

**E1.2** Data: Median length over time, with confidence limits and possibly
         overlaid with (Results) a line showing median length in the model
         population?

**E2.1** Results: Population numbers at age as a table and/or bubble plot?

**E2.2** Results: Also plot CPUE by year instead of quarters?

---

## Comments/questions for the SAM team:

Now:

* Was M changed at the CondAge step in the 2020 model development?

Later:

* Add a diagnostic to the data inputs report, identifying tag release groups
  that have recapture rates lower than a given threshold.

* Add a table/plot showing tag releases and recoveries by 9x9 region.

## Sources for additional questions

F: SC 2022 discussion items

G: Summary Report from 2020

H: Matt's powerpoint
