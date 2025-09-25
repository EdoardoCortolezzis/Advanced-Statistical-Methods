# Advanced Statistical Methods — Project

**Author:** Edoardo Cortolezzis  
**Course:** Advanced Statistical Methods  

This repository contains the source and rendered reports for my course project.  
The project is organized as a four-part, hands-on tour through core topics in modern applied statistics:

1. **Multilevel Modeling** — hierarchical GLMMs for count data (Poisson & Negative Binomial) with varying intercepts across grouping factors.  
2. **Causal Inference** — exploratory and modeling workflow for treatment effect analysis (incl. pre/post visualization).  
3. **Semiparametric Regression** — flexible regression via smooth functions/splines.  
4. **Mixed Membership Models** — introduction and application notes.

> The single R Markdown file `whole_project.Rmd` compiles the entire project; each chapter is also available as a standalone HTML report.

---

## Repository Structure

├── whole_project.Rmd # Master R Markdown for the full project
├── 1_HM.html # 1. Multilevel modeling (rendered)
├── 2_CI.html # 2. Causal Inference (rendered)
├── 3_semiparametric.html # 3. Semiparametric Regression (rendered)
└── 4_mixed_memebership.html # 4. Mixed Membership Models (rendered)


- **Multilevel Modeling** (`1_HM.html`): Fits hierarchical models for counts using Bayesian GLMMs with `stan_glmer`, comparing Poisson and Negative Binomial specifications and random intercepts for multiple grouping factors.  
  _Rendered report:_ `1_HM.html`

- **Causal Inference** (`2_CI.html`): Starts from data exploration (e.g., pre vs. post test scatter with a regression line) and proceeds to treatment-effect estimation workflow and diagnostics.  
  _Rendered report:_ `2_CI.html`

- **Semiparametric Regression** (`3_semiparametric.html`): Demonstrates smoothing-based modeling (e.g., spline terms) to capture nonlinear effects, with interpretation and visualization.  
  _Rendered report:_ `3_semiparametric.html`

- **Mixed Membership Models** (`4_mixed_memebership.html`): Presents the intuition and a worked example of mixed-membership modeling, including interpretation of the resulting latent structure.  
  _Rendered report:_ `4_mixed_memebership.html`

---

Results Snapshot
Multilevel GLMMs: Bayesian Poisson and Negative Binomial models with varying intercepts across eth, precinct, and eth:precinct. Model summaries include posterior medians and dispersion for NegBin fits.

Causal Exploration: Pre/post relationships visualized with a fitted regression line to motivate identification and model choice.

Semiparametric Fits: Smoother-based effects (splines) to capture nonlinear patterns.

Mixed Membership: Latent structure summarized and interpreted.

