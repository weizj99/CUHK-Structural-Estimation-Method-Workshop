# CUHK Structural Estimation Method Workshop

**Connecting economic models, data, and estimation.**

This workshop connects economic models to data through parameter estimation and quantitative analysis. The emphasis is on implementation: how the methods work and how they are used in research. This repository collects eight sets of lecture slides and selected readings.

## Learning path

> Economic question → model and data → estimation and computation → quantitative implications

The first four lectures introduce estimation methods and computational tools. The next four turn to research applications and extensions, including tax policy, trade and migration, heterogeneity, and frictions.

### Part I · Methods and computation

Start with how models connect to data, then study likelihood and moment-based estimation. The final lecture in this part introduces deep learning surrogates for model computation.

| Lecture | Topic | Materials |
| --- | --- | --- |
| 1 | Introduction, sufficient statistics, and calibration | [Slides](Lec1_Introduction_SuffStat_Calibration.pdf) · [Reading](#lecture-1) |
| 2 | Maximum likelihood estimation and bootstrap | [Slides](Lec2_MLE_and_Bootstrap.pdf) · [Reading](#lecture-2) |
| 3 | Generalized method of moments and simulated method of moments | [Slides](Lec3_GMM_SMM.pdf) · [Reading](#lecture-3) |
| 4 | Deep learning surrogates | [Slides](Lec4_Deep_Learning_Surrogates.pdf) · [Reading](#lecture-4) |

### Part II · Applications and extensions

Use the methods above to read applied research: connect the economic question to the model, understand how its parameters are estimated, and examine the resulting quantitative analysis.

| Lecture | Topic | Materials |
| --- | --- | --- |
| 5 | Notching R&D investment with corporate income tax cuts in China | [Slides](Lec5_Notching_R_D_Investment_with_Corporate_Income_Tax_Cuts_in_China_tex.pdf) · [Paper](https://www.aeaweb.org/articles?id=10.1257/aer.20191758) |
| 6 | Trade, migration, and productivity | [Slides](Lec6_Trade_Migration_Productivity.pdf) · [Paper](https://www.aeaweb.org/articles?id=10.1257/aer.20150811) |
| 7 | Distribution framework and heterogeneity | [Slides](Lec7_Distribution_Framework_Heterogeneity.pdf) |
| 8 | Diffuse bunching with frictions | [Slides](Lec8_Diffuse_Bunching_with_Frictions.pdf) |

## Readings by lecture

These links point to the material relevant to each lecture. PDF page numbers count from the first page of the file; external lecture numbers refer to the source course.

### Lecture 1

- [Chetty — Sufficient Statistics for Welfare Analysis: “General Framework,” PDF p. 17](https://rajchetty.com/wp-content/uploads/2021/04/slides_areview_suffstat.pdf#page=17).
- [Tomás R. Martinez — Calibration and the Use of Data in Macroeconomics: “Calibration,” PDF pp. 6–10](https://tomasrm.github.io/teaching/quantmacro/data_macro.pdf#page=6).
- Further reading: [Kennedy and O’Hagan — Bayesian Calibration of Computer Models, Section 1: “Overview”](https://www.asc.ohio-state.edu/statistics/comp_exp/jour.club/kennedy01.pdf#page=1).

### Lecture 2

- [Braun — external Lecture 5: Maximum Likelihood Estimation](https://christine-braun.github.io/Lecture_Notes/WarwickLabor/MLE.pdf).
- [Mikusheva — Lecture 9: Bootstrap, “Bootstrap” section and resampling algorithm, PDF p. 2](https://ocw.mit.edu/courses/14-384-time-series-analysis-fall-2013/2fdf997bca65d6ed82ba7a94f6cdc970_MIT14_384F13_lec9.pdf#page=2).

### Lecture 3

- [Braun — external Lecture 6: Generalized Method of Moments](https://christine-braun.github.io/Lecture_Notes/WarwickLabor/GMM.pdf).
- [Braun — external Lecture 7: Simulated Method of Moments and Indirect Inference](https://christine-braun.github.io/Lecture_Notes/WarwickLabor/SMM.pdf).

### Lecture 4

- [DeepHAM — “Running” section](https://github.com/frankhan91/DeepHAM#running): an external implementation example, with a Krusell–Smith quick start and a second model example.

The paper links beside Lectures 5 and 6 lead to the original articles.

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
