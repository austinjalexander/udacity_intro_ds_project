# udacity_intro_ds_project

##Section 0
I did not use any references.

## Section 1. Statistical Test

### 1.1.a Which statistical test did you use to analyse the NYC subway data?

The Mann-Whitney $U$ test was used to determine if there was a statistically significant difference between the number of reported entries on rainy and non-rainy occasions. This nonparametric test of the equality of two population medians from independent samples was used since the distribution of entries is non-normal (right-skewed) and their shape is the same, as seen visually via histograms, probability plots, and box plots, and as the result of the Shapiro-Wilk normality test (see <a href='IntroDS-ProjectOne-DataExploration-Supplement.ipynb#prep-for-stats' target='_blank'>Preparation for Statistical Tests</a>). However, since the sample sizes are so large, the parametric Welch's $t$-test likely could have been used (and, it was implemented for confirmation purposes, along with the nonparametric Wilcoxon signed-rank test; both agreed with the Mann-Whitney $U$ test results).

1.1.b Did you use a one-tail or a two-tail P value?
1.1.c What is the null hypothesis?
1.1.d What is your p-critical value?


