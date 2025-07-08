# Difference-in-differences-DID-in-a-training-applied-to-a-sales-team
This repository contains a step-by-step, didactic analysis of a Difference-in-Differences (DiD) model applied to a real-world-inspired scenario: a sales training program applied to only part of a sales team.  The goal is to estimate the causal impact of the training on sales performance using Python and statistical modeling.

**About the Project**

We simulate a scenario where:

Team A receives a new sales training program.

Team B does not (control group).

We collect sales data before and after the intervention.

Using the DiD method, we estimate whether the improvement observed in Team A is actually due to the training — or simply reflects general trends.

**Key Concepts Covered**

What is Difference-in-Differences (DiD)?

The parallel trends assumption

Regression modeling for causal inference

Visual representation of the DiD components

Synthetic dataset generation

Interpretation of regression results

**File Structure:**

DIF.ipynb: Jupyter Notebook with full explanation, visuals, and regression modeling

(Optional) README.md: Overview and documentation.

**Tools and Libraries Used:**

pandas and numpy for data handling

statsmodels for linear regression modeling

matplotlib and seaborn for visualization

**Final Result**

The DiD estimator (interaction term in the regression) captures the causal effect of the sales training on performance.

In our example, the training program increased sales by approximately 10 units, after controlling for general time effects.

**License**

This project is released under the MIT License — feel free to use, modify, and share.

**Acknowledgments** 

This project was designed for educational purposes — to demonstrate causal inference using the DiD method in a clear and visual way.



