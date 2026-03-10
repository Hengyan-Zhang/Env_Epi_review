---
editor_options: 
  markdown: 
    wrap: 72
---

# Epidemiology Exam Summary

## Study Instruments, Bias, and Confounding

------------------------------------------------------------------------

# Key Exam Concepts

Common exam questions include:

1.  What are the three alternative explanations for an observed
    association?
    -   Bias
    -   Confounding
    -   Chance
2.  What does non-differential misclassification cause?
    -   Bias toward the null.
3.  In which study design is recall bias most common?
    -   Case-control studies.
4.  What are the three criteria for a confounder?
    -   Associated with exposure
    -   Associated with outcome
    -   Not on the causal pathway
5.  Methods to control confounding?
    -   Restriction
    -   Stratification
    -   Multivariable regression

------------------------------------------------------------------------

# 1. Study Instruments

Common tools used in epidemiological research:

-   **Questionnaire**
    -   Measures exposure, outcome, and confounders
-   **Diary**
    -   Diet, activities, behaviors
-   **Registry data**
    -   Population registry, cancer registry
-   **Clinical examination**
    -   Anthropometric measurements (height, weight, blood pressure)
-   **Biomonitoring**
    -   Blood samples, biomarkers (e.g., blood lead concentration)
-   **Ambient sampling**
    -   Environmental exposure (e.g., dust samples)
-   **Job Exposure Matrix (JEM)**
    -   Expert-based occupational exposure estimation

Example: Exposure to lead → measured using **blood samples
(biomonitoring)**

------------------------------------------------------------------------

# 2. Reliability vs Validity

## Reliability

Reliability refers to the **consistency of a measurement**.

If the measurement is repeated multiple times and produces similar
results, it has high reliability.

Example: Repeated blood pressure measurements producing similar values.

## Validity

Validity refers to the **accuracy of a measurement**.

It indicates whether the measurement reflects the **true value**.

Example: A diagnostic test correctly identifying asthma patients.

## Classic Scenarios

| Situation | Interpretation |
|------------------------------------|------------------------------------|
| Reliable but not valid | Measurements are consistent but incorrect |
| Low reliability & low validity | Measurements are inconsistent and inaccurate |
| Reliable and valid | Measurements are both accurate and consistent |

------------------------------------------------------------------------

# 3. Why Study Results Might Be Incorrect

Observed associations may not represent the true causal relationship.

Three main alternative explanations:

-   **Bias**
-   **Confounding**
-   **Chance (random error)**

------------------------------------------------------------------------

# 4. Misclassification

Misclassification occurs when individuals are assigned to the wrong
exposure or disease category.

Example: An exposed individual recorded as non-exposed.

## Non-differential Misclassification

Definition: Random measurement error affecting all groups equally.

Characteristics:

-   Same probability of misclassification in cases and controls.
-   Common in imperfect measurement instruments.

Effect:

Bias **toward the null** (effect estimate moves toward OR = 1).

Key exam statement:

Non-differential misclassification **attenuates associations**.

Solutions:

Improve measurement; Increase sample size.

## Differential Misclassification

Definition: Systematic measurement error affecting groups differently.

Characteristics:

-   Misclassification probability differs between cases and controls.

Effect:

May **overestimate or underestimate** the true association.

Result is **unpredictable**.

Solutions:

Improve measurement;Blind the observes and subjects to exposure/outcome/internvention status.

------------------------------------------------------------------------

# 5. Selection Bias

Definition:

Selection bias occurs when systematic differences exist between
individuals selected for a study and those not selected.

This results in a study population that does not represent the target
population.

## Types of Selection Bias

### Sampling Bias

Occurs when the sampling strategy excludes certain groups.

Example:

Study question: Precarious work → depression

Sampling frame: Tax office income tax registry

Problem:

People with precarious employment may not pay taxes and are therefore
not included.

Result:

Underrepresentation of the exposed group.

Effect:

**Underestimation of the risk factor**.

------------------------------------------------------------------------

### Participation Bias (Non-response bias)

Occurs when participation differs according to exposure or outcome.

Example:

Case-control study:

Asbestos exposure → ovarian cancer

Participation rates:

Cases: 90% Controls: 50%

If low-exposure controls are less likely to participate:

Exposure prevalence in controls appears higher.

Effect:

**Underestimation of the true association**.

Participation bias may also lead to **overestimation** depending on
participation patterns.

------------------------------------------------------------------------

# 6. Reducing Selection Bias

Methods to improve participation:

-   Send reminders
-   Provide incentives (vouchers)
-   Provide personal study results
-   Use priority mail
-   Increase perceived relevance of the study
-   Maintain contact with cohort participants

Assessing selection bias:

-   Compare responders and non-responders
-   Use registry data
-   Use non-responder questionnaires
-   Apply inverse probability weighting

------------------------------------------------------------------------

# 7. Recall Bias

Recall bias is a form of **information bias**.

Definition:

Systematic differences in the accuracy or completeness of participant
recall.

Most common in **case-control studies**.

Example:

Study: Asbestos exposure → ovarian cancer

Exposure measurement: Self-reported questionnaire.

Cases may search for explanations for their disease and report exposures
more often.

Controls have no such motivation.

Result:

Cases report higher exposure frequency.

Effect:

**Overestimation of the association**.

------------------------------------------------------------------------

# 8. Confounding

Definition:

Confounding occurs when the association between exposure and outcome is
distorted by a third variable.

Example:

Coffee consumption → lung cancer

True confounder:

Smoking

Smokers drink more coffee and have higher lung cancer risk.

Coffee itself may not cause lung cancer.

------------------------------------------------------------------------

## Conditions for a Confounder

A variable is a confounder if it:

1.  Is associated with the exposure
2.  Is associated with the outcome
3.  Is not part of the causal pathway

------------------------------------------------------------------------

# 9. Identifying Potential Confounders

Strategies:

-   Review existing literature
-   Identify common confounders
    -   Age
    -   Sex
    -   Socioeconomic status
-   Apply subject-matter knowledge

Examples in occupational epidemiology:

-   Smoking
-   Physical fitness

------------------------------------------------------------------------

# 10. Confounding vs Effect Measure Modification

## Confounding

After stratification:

Association disappears.

Example:

Overall OR = 2.0

After stratifying by smoking:

OR = 1.0 in both strata.

Interpretation:

The observed association was due to confounding.

## Effect Measure Modification (Interaction)

The effect differs across strata.

Example:

Non-smokers: OR = 1.0 Smokers: OR = 4.0

Interpretation:

Smoking modifies the effect of the exposure.

Unlike confounding, effect modification should be **reported rather than
controlled away**.

------------------------------------------------------------------------

# 11. Controlling for Confounding

Methods:

### Restriction

Limit study population to one category.

Example:

Include only non-smokers.

Limitation:

Loss of generalizability.

### Stratification

Analyze exposure-outcome association within strata of the confounder.

Example:

Stratify by smoking status.

### Multivariable Analysis

Adjust for confounders using statistical models.

Examples:

-   Logistic regression
-   Cox regression
-   Linear regression

------------------------------------------------------------------------

# 12. Chance (Random Error)

Random variation may lead to incorrect conclusions.

Strategies to reduce chance:

-   Increase sample size
-   Perform statistical tests
-   Calculate confidence intervals
