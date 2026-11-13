# Statistics for Biologists

## Introduction and overview

Developed practical skills in R, statistical modelling and experimental design, using biological and health-related teaching datasets to investigate variation, evaluate evidence and quantify uncertainty.

The module combined probability and statistical inference with regression, Bayesian reasoning, likelihood-based methods and the challenges of genomic data. Applications included protein composition, DNA methylation, planning gene-expression studies and genomic prediction using simulated data.

## Skills developed

- **R programming and automation:** Used scripts, functions, loops and notebooks to process data, run simulations and build repeatable analyses.
- **Statistical modelling:** Fitted regression, ANOVA and mixed-effects models, interpreted coefficients and assessed model assumptions.
- **Inference and uncertainty:** Applied hypothesis tests, maximum likelihood estimation, bootstrapping and Bayesian reasoning to evaluate evidence and uncertainty.
- **Experimental design:** Used power analysis to plan sample sizes, accounting for biological variability, multiple testing and study costs.
- **Genomic analysis:** Estimated allele frequencies from sequencing counts and explored genomic prediction using simulated genotype data.
- **Critical interpretation:** Distinguished association from causation and statistical significance from biological relevance, and evaluated predictions on data excluded from model fitting.
- **Visualisation and communication:** Produced clear figures, model diagnostics and written explanations of methods, findings and limitations.

## 1. Introduction to R and RStudio

- **R programming and data handling:** Wrote scripts, worked with vectors, matrices, lists and data frames, and filtered observations using logical conditions.
- **Automation and problem-solving:** Created and tested reusable functions and loops to perform calculations, simulate population growth and visualise results.

## 2. Probability Theory and Distributions

- **Probability modelling:** Applied set operations, conditional probability and independence, and explored discrete and continuous distributions, including binomial, exponential and normal distributions.
- **Biological sequence analysis:** Calculated amino-acid probabilities in a collagen protein sequence and used sliding windows to examine how composition varied along the sequence.

## 3. Statistical Inference

- **Exploratory data analysis:** Classified variables, calculated descriptive statistics and selected appropriate plots to examine distributions, variation and potential outliers.
- **Parameter estimation:** Used repeated sampling to compare estimators of mean blood pressure, assessing their performance through bias and mean squared error.

## 4. Statistical Testing

- **Hypothesis testing:** Formulated null and alternative hypotheses and applied chi-squared tests of independence and goodness of fit, alongside paired and independent-sample t-tests.
- **Uncertainty and statistical power:** Used bootstrap resampling to estimate confidence intervals, and simulations to explore statistical power, error rates and the influence of sample size.

## 5. Linear Models

- **Correlation and regression:** Measured associations using Pearson correlation and fitted linear models, interpreting coefficients, predictions and residual variation.
- **ANOVA and model assessment:** Examined categorical and continuous effects and interactions, checked diagnostic plots and refined a DNA methylation model using age and mouse strain.

## 6. Introduction to Bayesian Inference

- **Bayesian reasoning:** Applied base rates and conditional probability to evaluate how evidence changes the probability of a hypothesis.
- **Interpreting DNA evidence:** Compared individual match probabilities with the chance of finding at least one match in a large database, highlighting the importance of context.

## 7. Likelihood

- **Maximum likelihood estimation:** Constructed and plotted likelihood and log-likelihood functions to identify best-fitting model parameters.
- **Sequencing data analysis:** Estimated minor allele frequencies from pooled read counts and implemented likelihood ratio tests to assess proposed allele frequencies.

## 8. Representing Uncertainty Using Regression

- **Variation and uncertainty:** Used simulated apple-weight data to distinguish variation between observations from uncertainty in estimated means.
- **Regression and simulation:** Compared models with and without an intercept to interpret coefficient standard errors, and used repeated ANOVA simulations to explore false positives.

## 9. Experimental Design

- **Study planning:** Proposed a two-stage gene-expression study combining RNA-seq discovery with independent RT-qPCR validation, considering control variables, biological replication, multiple testing and cost.
- **Power analysis:** Used the R package `pwr` to calculate sample-size requirements and explore how variability, effect size and significance thresholds influence power.

## 10. Big Data Challenges of Genomic Data

- **Mixed-effects modelling:** Used `nlme` to fit random intercepts and slopes for grouped data and understand how shrinkage shares information across groups.
- **Genomic prediction:** Used `rrBLUP` with simulated genotype data containing more predictors than individuals, and compared training predictions with performance on held-out individuals.