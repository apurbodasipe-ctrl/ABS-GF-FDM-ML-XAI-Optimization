# Machine Learning Assisted Multi-Objective Optimization of ABS–Glass Fiber FDM Process Parameters

## Project Overview

This repository presents a machine learning-based framework for predicting, interpreting, and optimizing the performance of ABS–glass fiber reinforced Fused Deposition Modeling (FDM) additive manufacturing processes.

The developed framework integrates experimental data analysis, design of experiments (DOE), machine learning-based surrogate modeling, explainable artificial intelligence (XAI), sensitivity analysis, uncertainty evaluation, and multi-objective optimization.

The primary objective of this research is to identify optimal FDM processing conditions by improving tensile strength while reducing surface roughness through a data-driven optimization approach.

---

# Research Objectives

- Develop predictive models for tensile strength and surface roughness.
- Compare multiple machine learning algorithms for FDM performance prediction.
- Identify the most influential process parameters affecting part quality.
- Interpret machine learning predictions using explainable AI techniques.
- Evaluate parameter sensitivity using global sensitivity analysis.
- Determine optimal processing conditions using NSGA-II multi-objective optimization.

---

# Research Workflow

![Research Workflow](assets/workflow.png)

The complete workflow consists of:

Experimental Data Collection  
↓  
Data Processing and Analysis  
↓  
Design Space Exploration  
↓  
Machine Learning Model Development  
↓  
Explainable AI Analysis  
↓  
Sensitivity Analysis  
↓  
NSGA-II Multi-Objective Optimization  
↓  
Optimal Process Parameter Identification

---

# Input Process Parameters

The framework considers major FDM processing parameters:

- Glass fiber content
- Infill density
- Layer thickness
- Nozzle temperature
- Bed temperature
- Printing speed

---

# Output Responses

The optimization targets are:

- Tensile strength (MPa)
- Surface roughness (µm)

---

# Machine Learning Framework

Multiple machine learning algorithms were evaluated, including:

- XGBoost
- CatBoost
- Extra Trees
- Random Forest
- Gradient Boosting
- Support Vector Regression
- Neural Network models

The best-performing models were further optimized and integrated into ensemble surrogate models for reliable prediction.

---

# Model Prediction Performance

## Tensile Strength Prediction

![Tensile Prediction](assets/Tensile_Test_Observed_vs_Predicted.png)


## Surface Roughness Prediction

![Surface Roughness Prediction](assets/Roughness_Test_Observed_vs_Predicted.png)

---

# Explainable Artificial Intelligence (XAI)

SHAP-based explainability analysis was performed to understand the contribution of individual process parameters and improve the transparency of machine learning predictions.

## Tensile Strength Feature Importance

![Tensile SHAP](assets/Tensile_SHAP_Beeswarm.png)


## Surface Roughness Feature Importance

![Roughness SHAP](assets/Roughness_SHAP_Beeswarm.png)

---

# Sensitivity Analysis

Global sensitivity analysis using the Sobol method was conducted to quantify the individual effects and interactions of FDM process parameters.

![Sobol Sensitivity](assets/Tensile_Sobol_ST_Bar.png)

---

# Multi-Objective Optimization

The NSGA-II algorithm was applied to achieve a balanced trade-off between:

- Maximizing tensile strength
- Minimizing surface roughness

![Pareto Front](assets/Fig1_Nominal_Pareto_Front.png)

---

# Robust Optimization

Uncertainty-aware optimization and TOPSIS-based decision making were applied to identify robust process conditions.

![Robust Optimization](assets/Fig2_Robust_Pareto_TOPSIS.png)

---

# Repository Structure
