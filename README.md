# Berlin Marathon Performance Analysis

This project analyzes marathon finish times of female participants in the **Berlin Marathon**, focusing on age-related differences across six age groups. The study employs statistical techniques to identify significant patterns and trends in marathon performance.

## Project Overview

The Berlin Marathon is a globally recognized endurance event that draws thousands of participants annually. This study explores performance differences based on age group, leveraging a dataset of 2,829 entries. Key objectives include:

1. Summarizing finish time distributions across age groups using descriptive statistics.
2. Testing for significant differences in finish times between age groups using **One-Way ANOVA**.
3. Conducting post-hoc pairwise comparisons using **Bonferroni Correction** and **Tukey’s Honest Significant Difference (HSD)**.

## Dataset

The dataset is sourced from the **Berlin Marathon Dataset (2024)** and includes:
- **Age Group**: Participants categorized into six groups (30, 35, 40, 45, 50, 55).
- **Finish Time**: Marathon completion time in seconds.

### Data Quality
- Complete dataset with no missing values.
- Preprocessing included formatting corrections and range validation for finish times.

## Statistical Methods

### Assumption Tests
- **Normality**: Shapiro-Wilk Test.
- **Homogeneity of Variances**: Levene’s Test.

### Hypothesis Testing
- **One-Way ANOVA**: To determine if mean finish times differ across age groups.

### Post-Hoc Analysis
- **Bonferroni Correction**: A conservative method for multiple comparisons.
- **Tukey’s HSD**: Provides confidence intervals and insights into pairwise differences.

## Tools and Libraries

The analysis is conducted using **Python 3.12.0**, with the following libraries:
- **Pandas**: Data manipulation.
- **NumPy**: Numerical computations.
- **Matplotlib & Seaborn**: Visualizations.
- **SciPy & Statsmodels**: Statistical tests and models.

## Key Findings

1. Finish times increase with age, indicating longer times for older participants.
2. Significant differences were observed between younger (30, 35) and older age groups (50, 55).
3. Tukey’s HSD identified more nuanced differences compared to Bonferroni Correction, providing confidence intervals for interpretation.
