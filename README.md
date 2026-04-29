# Physical Activity & Body Weight Analysis

Investigated whether physical activity frequency is associated with body weight using 2,111 health records from Mexico, Peru, and Colombia. Applied a Welch's two-sample t-test in R and found statistically significant evidence (p = 0.002) that low-activity individuals weigh more on average.

**[View the Full Report](https://chapagetteisgood.github.io/physical-activity-analysis/)**

## Key Findings

- Welch's two-sample t-test: t = 3.10, p = 0.002
- 95% confidence interval for mean weight difference: [1.49, 6.61] kg
- Low-activity individuals (FAF < 1.5) weigh significantly more than high-activity individuals

## Tools

R, ggplot2, dplyr

## Dataset

[Obesity Levels Dataset](https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition) from the UCI Machine Learning Repository. 2,111 records with variables including weight, physical activity frequency, gender, age, and height.

## Author

Vincent Pham - Data Science, University of Wisconsin-Madison
