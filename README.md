# Machine Learning Assisted Multi-Objective Optimization of ABS–Glass Fiber FDM Process Parameters

## Overview

This repository presents a thesis-style research project on the data-driven prediction, interpretation, and optimization of **ABS–glass fiber reinforced fused deposition modeling (FDM)** process parameters. The work integrates **experimental data analysis**, **virtual design-space exploration**, **machine learning-based surrogate modeling**, **explainable artificial intelligence (XAI)**, **global sensitivity analysis**, and **multi-objective optimization** to improve printing performance.

The central motivation of this study is that FDM process outcomes are governed by highly coupled parameters such as material composition, thermal conditions, deposition strategy, and geometric settings. Because these interactions are nonlinear and often competing in nature, conventional one-factor-at-a-time optimization becomes inefficient. To address this challenge, this project develops an AI-assisted framework capable of:

- predicting **tensile strength**
- predicting **surface roughness**
- interpreting model behavior through **SHAP-based explainability**
- quantifying parameter influence via **Sobol sensitivity analysis**
- identifying optimal printing conditions using **NSGA-II multi-objective optimization**

This repository is therefore not only a modeling exercise, but a complete **research workflow** for intelligent FDM process design and decision support.

---

## Research Objectives

The specific objectives of this project are:

1. To develop predictive models for **tensile strength** and **surface roughness** in ABS–GF FDM printing.
2. To compare multiple machine learning algorithms and identify the most robust predictive framework.
3. To investigate the relative importance of process variables using explainable AI methods.
4. To quantify the sensitivity and interactions of input parameters through variance-based global sensitivity analysis.
5. To formulate a multi-objective optimization framework that simultaneously:
   - **maximizes tensile strength**
   - **minimizes surface roughness**
6. To identify robust process windows under uncertainty for practical engineering application.

---

## Problem Context

Fused deposition modeling remains one of the most widely used additive manufacturing techniques due to its low cost, flexibility, and accessibility. However, its output quality is strongly dependent on process parameter selection. In glass-fiber-filled polymer systems, this challenge becomes more complex because reinforcement content interacts with thermal and deposition parameters, affecting both structural performance and surface finish.

In this project, the FDM process is studied through a combination of **experimental observations** and **simulation-assisted virtual design exploration**, enabling a more comprehensive search across the design space than would be feasible through physical testing alone.

---

## Input Parameters and Output Responses

### Input Parameters
The study considers the following major process variables:

- Glass fiber content
- Infill density
- Layer thickness
- Nozzle temperature
- Bed temperature
- Printing speed

### Output Responses
The optimization targets are:

- **Tensile strength (MPa)** → to be maximized
- **Surface roughness (µm)** → to be minimized

---

## Methodological Framework

The developed methodology follows a sequential and integrated research pipeline:

1. **Experimental data acquisition and preprocessing**
2. **Design-space analysis and virtual DOE generation**
3. **Virtual response simulation for broader design coverage**
4. **Machine learning model benchmarking and tuning**
5. **Final surrogate model development**
6. **Explainable AI analysis using SHAP and permutation importance**
7. **Global sensitivity analysis using Sobol indices**
8. **Multi-objective optimization using NSGA-II**
9. **Robust optimization and engineering decision support using TOPSIS**

This framework enables both predictive accuracy and interpretability, which are essential for reliable engineering optimization.

---

## Repository Structure

```text
ABS-GF-FDM-ML-XAI-Optimization
│
├── Code
│   └── Jupyter notebooks for preprocessing, simulation, ML, XAI, sensitivity analysis, and optimization
│
├── Data
│   └── Experimental datasets, processed datasets, and generated virtual samples
│
├── Results
│   └── Output figures, performance plots, and optimization results
│
└── assets
    └── Publication-quality figures used in this README
