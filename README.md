# Physical Activity & Body Weight Analysis

Investigated whether physical activity frequency is associated with body weight using a dataset of 2,111 health records from Mexico, Peru, and Colombia. Applied a Welch's two-sample t-test in R and found statistically significant evidence (p = 0.002) that individuals with lower physical activity levels weigh more on average.

> Course project for STAT 240 - Introduction to Data Modeling (University of Wisconsin-Madison, Fall 2025)

## Key Findings

- Segmented participants into low activity (FAF < 1.5) and high activity (FAF >= 1.5) groups
- Welch's two-sample t-test: t = 3.10, p = 0.002
- 95% confidence interval for the mean weight difference: [1.49, 6.61] kg
- Low-activity individuals weigh significantly more on average than high-activity individuals

## Tools and Methods

- Language: R
- Libraries: ggplot2, dplyr
- Statistical Methods: Welch's two-sample t-test, confidence intervals, exploratory data analysis
- Visualizations: Boxplots, scatter plots

## Dataset

- Source: Obesity Levels Dataset (UCI Machine Learning Repository)
- Records: 2,111 individuals
- Key Variables: Weight (kg), FAF (physical activity frequency), Gender, Age, Height

## Project Structure

- data/ - Raw dataset
- output/ - Final HTML report

## How to Run

1. Clone the repository
2. Open the HTML report in output/ to view the full analysis

## Author

Vincent Pham
