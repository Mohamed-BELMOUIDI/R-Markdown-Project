# Coursera Statistical Inference Project

This project is divided into two main components:

1. **Simulation Exercise**
2. **Basic Inferential Data Analysis**

Your task is to generate a report that addresses the given questions. Ideally, you should use **knitr** to create the report and convert it to a PDF. However, you are welcome to use any software you prefer to create the final PDF. The report should not exceed **3 pages**, and if necessary, you can add **3 pages** for supplementary materials such as code, figures, etc.

### Part One: Simulation Exercise

In this section, you will explore the **exponential distribution** in **R** and compare it with the **Central Limit Theorem**. The exponential distribution can be simulated in R using the function `rexp(n, lambda)`, where **lambda** is the rate parameter. The mean of this distribution is \( \frac{1}{\lambda} \) and its standard deviation is also \( \frac{1}{\lambda} \).

- **Set lambda = 0.2** for all simulations.
- Investigate the distribution of averages of **40 exponentials** through **1000 simulations**.

Illustrate and explain the following properties of the distribution of the mean of 40 exponentials:

- **Sample Mean:** Compare it to the theoretical mean of the distribution.
- **Sample Variability:** Examine the variance and compare it to the theoretical variance.
- **Normality:** Demonstrate that the distribution of the sample mean is approximately normal.

### Part Two: Inferential Data Analysis

In this part, you will load the **ToothGrowth** dataset and perform basic exploratory data analysis:

- **Summarize the data** with descriptive statistics.
- Use **confidence intervals** and/or **hypothesis tests** to compare tooth growth across different supplement types and doses (stick to the techniques covered in class, even if other methods might be appropriate).
- **Conclusions:** State your findings and the assumptions made during the analysis.
