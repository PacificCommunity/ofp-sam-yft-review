# List of Recommendations from the Independent Review of Recent (2020) WCPO Yellowfin Tuna Assessment

Sourced from from Appendix H of WCPFC-SC19-2023/SA-WP-01

## 1. Resourcing

The analysts be given more time or additional technical support

## 2. Model Changes

Each step in the bridging analysis should involve only one change

## 3. Natural Moratality

Keep the current approach, but with alternative base values for M in the uncertainty grid 

## 4. Growth

Estimate growth internally using conditional age-at-length data

## 5. Size composition

Review input sample size units (shots/trips), maximum input caps and weighting

## 6. CPUE

Explore shared catchability, selectivity, regional weighting and high values in the north and south

## 7. Effort Creep

Try to develop models based on technological changes in asociation with DWFN

## 8. Tagging data

More tag seeding experiments and continue exploring variable

# Initial list

## Rec 1 (p. 3)

Analysts be given more time or additional technical support to ensure that model
exploration is such that it is possible to fully understand the changes in model
results. Stepwise model development should involve a single change along with
minor changes to MFCL settings to ensure convergence, all clearly documented.

## Rec 2 (p. 3)

A table documenting changes to model specifications be adopted for future
assessments, similar to Table 1 in the review report.

## Rec 3 (p. 3)

Adding alternative cases for base M in the uncertainty grid, using the current
approach with the base M set to 0.2 as the diagnostic case.

## Rec 4 (p. 4)

Not basing the growth curve on an external estimate unless internal estimates
are clearly implausible, unless the growth curve is externally estimated using
conditional age-at-length data.

## Rec 5 & 6 (p. 6)

That the SPC is supported to conduct further investigation of effort creep in
the longline and purse seine fisheries.

That the upcoming SPC research on effort creep in pole and line and purse seine
fisheries should also consider longline fisheries.

## Rec 7 (p. 7)

For selectivity:

- define fisheries using a regression tree analysis applied to size comps

- describe fisheries, magnitude, sample size, whether it's used as index

- remove unrepresentative/unreliable data (fisheries, years, lengths)

- avoid multimodal size comps and shoulders, by separating into more fisheries

- assume selectivity is generally length-based

- ensure that the model fits the bulk of the size comps (where most data are)

- consider downweighting size comps for fisheries with low catches

- fit the composition data for indices well, using flexible selectivities

- use empirical selectivity diagnostic (roliveros-ramos/empirical.selectivity)

- use empirical selectivity method to determine number and position of knots

- consider removing size comps for fisheries with low catches

## Rec 8 (p. 9)

For the 2023 assessment:

- development of a conceptual model, summarizing the size comps and CPUE, what
  tags tell about movement, whether juveniles seem to migrate differently from
  adults, genetics and other indicators of stock structure, oceanographic
  effects on distribution

- analysis of size comps based on Maunder et al. (2022)

- from this process, design simpler models and compare with more complex model

- identify realism constraints based on the conceptual model, e.g., the
  estimated recruitment in different regions

- avoid multiple fisheries based on the same gear in the same region, unless tag
  returns require them

- calculate the parameter covariance matrix from the Hessian to evaluate which
  parameter estimates are confounded

In addition, the panel recommends:

- implementing a single-area model that uses only data from the equatorial
  region (7, 3, 4, 8) both in MFCL and Stock Synthesis

- allowing juvenile movement rates to differ from adults (which may be zero)

- methods to integrate information from tagging recoveries

## Rec 9 (p. 12)

A CPUE likelihood option be developed in MFCL where the variance of log(CPUE) is
CV + overdispersion variance.

## Rec 10 (p. 12)

That orthogonal polynomial recruitment only be used for data-poor situations, or
for the earlier data-poor years.

## Rec 11 (p. 12)

That Dirichlet-multinomial be considered alongside the robust normal and
McAllister-Ianelli tuning. The Panel notes that all methods for weighting
composition data depend on 'stage-1' sample sizes and emphasizes the importance
of specifying these correctly. [sampled trips, sets, etc.]
