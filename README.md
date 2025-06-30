# State-Level Premature Mortality Risk: Evaluating Health Determinants While Controlling for Socioeconomic Factors In the United States

## Overview

This research project investigates how health determinants interact to affect state-level premature mortality rates after controlling for socioeconomic factors in the United States. The study aims to develop a comprehensive explanatory model that can be used for quantitative prediction of mortality risks across different states.

## Research Objectives

The primary purpose of this study is to:
- Offer a novel perspective to recognise states with higher mortality risks
- Orient public health and socioeconomic improvement initiatives at the state level
- Provide evidence-based insights for targeted interventions

## Research Question

**"How do healthy determinants interact to affect state-level premature mortality rates after controlling for socioeconomic factors in the United States?"**

## Methodology

### Key Variables
- **Health Determinants**: Mental distress, food insecurity, diabetes, motor-vehicle mortality rate, insufficient sleep
- **Confounding Factors**: Age over 65, Age less than 18
- **Control Variables**: Not Proficient in English, Median Household Income

### Analytical Approach
The study employs multiple analytical methods:
1. **Factor Analysis Model** - To identify latent risk factors
2. **Two Linear Regression Models** - For comparative analysis and validation
3. **Model Evaluation** - Using fit indices and explanatory power metrics

## Hypotheses

### H1: Latent Risk Factor Formation
Mental distress, food insecurity, diabetes, motor-vehicle mortality rate, and insufficient sleep form a single latent risk factor (MR1) through factor analysis, with model fit indices meeting acceptable thresholds.

### H2: Multivariate Association
In a multivariate linear regression (Model 1) of premature mortality on MR1, the latent risk factor will exhibit a significant positive association and explain a non-zero proportion of variance (R² > 0).

### H3: Confounding Effects
Confounding variables will confound the association between MR1 and mortality, while simultaneously exerting an independent effect on mortality.

### H4: Model Comparison
Linear Model 2 incorporating confounding factors and control variables, will exhibit greater interpretability and explanatory power than Linear Model 1.

## Expected Outcomes

This research aims to distil multiple correlated risk indicators into an overall risk factor that could influence premature mortality at the state level in the United States, providing valuable insights for public health policy and intervention strategies.

## Data Requirements

The study utilises:
- State-level health and mortality data
- Socioeconomic indicators by state
- Demographic variables for confounding control
- Literature review findings for model validation

## Applications

Results from this study can be used to:
- Identify high-risk states for targeted interventions
- Inform public health resource allocation
- Guide policy development for mortality reduction
- Support evidence-based decision making in healthcare planning

## Repository Structure

```
├── data/              # Raw and processed datasets
├── analysis/          # Statistical analysis scripts
├── models/            # Factor analysis and regression models
├── results/           # Output files and visualisations
├── documentation/     # Research documentation and literature review
└── README.md          # This file
```
=

*This research contributes to the understanding of state-level health disparities and provides a framework for identifying priority areas for public health intervention in the United States.*
