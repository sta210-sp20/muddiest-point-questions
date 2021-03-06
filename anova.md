ANOVA
================

### How do we find more practice problems?

For more practice problems on ANOVA, see [OpenIntro, 4th
edition](https://leanpub.com/openintro-statistics) the exercises in -
section 7.5: Comparing many means with ANOVA (pg. 295) - throughout
Chapter 7 exercises (pg. 299)

Note: The solutions to odd exercises are in the back of the book.

### Assumptions for ANOVA & Robustness

A statistical inference procedure is **robust** if it is still valid
even if there are departures (i.e. violations) from a particular
assumption. In other words, the procedure is robust if the confidence
intervals and/or p-values are very close to the stated values even if a
particular assumption is not met.

In the case of assumptions for ANOVA,

  - **Normality**: ANOVA is relatively robust against departures from
    Normaltiy unless the sample sizes are are small within each group.
    Therefore, as long as the sample sizes in each group are large
    enough, the p-values from ANOVA are still valid even if the
    distribution of the response in each group is extremely skewed or
    long-tailed.
    
      - Note: If there are departures from Normality in your analysis,
        you should note those departures when assessing the assumptions.
        If the sample sizes are relative large within each group
        (approx. greater than 10), then you can note the robustness of
        the ANOVA.

  - **Independence**: ANOVA is <u>not</u> robust against violations of
    the independence assumption, both within and between groups. If this
    assumption is violated a different analysis approach should be used.

  - **Constant (equal) variance**: ANOVA is <u>not</u> robust against
    violations of the constant (equal) variance assumption. If this
    assumption is violated, one should consider a transformation on the
    response variable (e.g. a log-transformation) or using another
    analysis approach. We will talk more about transformations in the
    coming weeks.

  - **Outliers**: Because ANOVA is all about analyzing means, it is
    <u>not</u> robust against extreme outliers. If there are extreme
    outliers in your data, you should consider removing them (thus
    limiting the scope of your analysis) or using a different anlaysis
    approach.

### More details about analysis after ANOVA:

  - Section 7.5.6 in [OpenIntro, 4th
    edition](https://leanpub.com/openintro-statistics): Multiple
    comparisions and controlling Type 1 Error rate (pg. 292)
  - Section 14.4 in [Statistical Modeling: A Fresh
    Approach](https://dtkaplan.github.io/SM2-bookdown/hypothesis-testing-on-whole-models.html):
    Interpreting the p-value

### When would we use ANOVA in practice?

Analysis of Variance is commonly used to analyze data from experimental
designs, most famously agricultural experiments.

In this class, we will most often use the Analysis of Variance framework
to compare two models as we decide which model best describes the
relationships between the response and predictor variables. We will talk
more about comparing models in the “Model Assessment” lecture in the
next few classes.

### More details on the F Distribution

  - Chapter 8 “F and R” in [A Compact Guide To Classical
    Inference](https://dtkaplan.github.io/CompactInference/private/f-and-r.html)
