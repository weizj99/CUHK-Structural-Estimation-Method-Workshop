# CUHK Structural Estimation Method Workshop

**Connecting economic models, data, and estimation.**

This workshop connects economic models to data through parameter estimation and quantitative analysis. The emphasis is on implementation: how the methods work and how they are used in research. This repository collects eight sets of lecture slides and selected readings.

## Learning path

> Economic question → model and data → estimation and computation → quantitative implications

The first four lectures introduce estimation methods and computational tools. The next four turn to research applications and extensions, including tax policy, trade and migration, heterogeneity, and frictions.

### Part I · Methods and computation

Start with how models connect to data, then study likelihood and moment-based estimation. The final lecture in this part introduces deep learning surrogates for model computation.

| Lecture | Topic | Slides |
| --- | --- | --- |
| 1 | Introduction, sufficient statistics, and calibration | [PDF](Lec1_Introduction_SuffStat_Calibration.pdf) |
| 2 | Maximum likelihood estimation and bootstrap | [PDF](Lec2_MLE_and_Bootstrap.pdf) |
| 3 | Generalized method of moments and simulated method of moments | [PDF](Lec3_GMM_SMM.pdf) |
| 4 | Deep learning surrogates | [PDF](Lec4_Deep_Learning_Surrogates.pdf) |

### Part II · Applications and extensions

Use the methods above to read applied research: connect the economic question to the model, understand how its parameters are estimated, and examine the resulting quantitative analysis.

| Lecture | Topic | Slides |
| --- | --- | --- |
| 5 | Notching R&D investment with corporate income tax cuts in China | [PDF](Lec5_Notching_R_D_Investment_with_Corporate_Income_Tax_Cuts_in_China_tex.pdf) |
| 6 | Trade, migration, and productivity | [PDF](Lec6_Trade_Migration_Productivity.pdf) |
| 7 | Distribution framework and heterogeneity | [PDF](Lec7_Distribution_Framework_Heterogeneity.pdf) |
| 8 | Diffuse bunching with frictions | [PDF](Lec8_Diffuse_Bunching_with_Frictions.pdf) |

## From reading to implementation

For each application, work through four questions:

1. **Model:** What is the economic question, and which assumptions and mechanisms address it?
2. **Data:** Which observations or moments inform the parameters?
3. **Estimation:** How are the model and estimator implemented, and what numerical difficulties arise?
4. **Results:** How well does the model fit the data, and what quantitative implications follow?

For hands-on study, read the paper's technical appendix and work through one key result. Compare it with the published result and trace any differences to the data, assumptions, or implementation.

## Selected references

- [Structural Estimation in Python](https://github.com/rickecon/StructEst_W20) — Richard W. Evans.
- [Topics in Labor Economics](https://christine-braun.github.io/teaching-labor.html) — Christine Braun.
- [Structural Estimation](https://users.ssc.wisc.edu/~ctaber/718/struct.pdf) — Christopher Taber.
- [Discrete Choice Methods with Simulation](https://eml.berkeley.edu/books/train1201.pdf) — Kenneth Train.

Please cite the original authors when using the linked papers, books, and teaching materials.
