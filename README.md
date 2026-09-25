# Machine Learning Assisted Multi-Objective Optimization of ABS–Glass Fiber FDM Process Parameters

## Project Overview

This repository presents a comprehensive machine learning-driven framework for predicting, interpreting, and optimizing the performance of ABS–glass fiber reinforced fused deposition modeling (FDM) additive manufacturing processes.

The developed framework integrates experimental data analysis, design space exploration, machine learning-based surrogate modeling, explainable artificial intelligence (XAI), global sensitivity analysis, uncertainty quantification, and multi-objective optimization to identify optimal FDM processing conditions.

The primary goal of this research is to simultaneously enhance mechanical performance (tensile strength) and improve surface quality (surface roughness) by understanding the complex relationships between printing parameters and final part performance.

---

# Research Workflow

The complete workflow consists of:

Experimental Dataset  
↓  
Data Preprocessing and Design Space Analysis  
↓  
Virtual Design of Experiments (DOE)  
↓  
Machine Learning Model Development  
↓  
Model Interpretation using SHAP and Feature Importance  
↓  
Global Sensitivity Analysis using Sobol Method  
↓  
NSGA-II Multi-Objective Optimization  
↓  
Robust Pareto-Optimal Process Window Identification


---

# Research Objectives

- Develop predictive models for tensile strength and surface roughness.
- Evaluate multiple machine learning algorithms for FDM performance prediction.
- Identify dominant process parameters influencing manufacturing outcomes.
- Apply explainable AI methods to improve model transparency.
- Quantify parameter sensitivity and interaction effects.
- Determine optimal printing conditions through multi-objective optimization.


---

# Input Process Parameters

The framework considers major FDM process variables:

- Glass fiber content
- Infill density
- Layer thickness
- Nozzle temperature
- Bed temperature
- Printing speed


# Output Responses

The optimization targets are:

- Tensile strength (MPa)
- Surface roughness (µm)


---

# Experimental Design Space

![Experimental Design](assets/Figure_01_Experimental_Design_Space_Coverage_600dpi.png)


---

# Machine Learning Prediction Performance

## Tensile Strength Prediction

![Tensile Prediction](assets/Tensile_Test_Observed_vs_Predicted.png)


## Surface Roughness Prediction

![Roughness Prediction](assets/Roughness_Test_Observed_vs_Predicted.png)


---

# Explainable Artificial Intelligence Analysis

SHAP analysis was performed to interpret model predictions and identify the contribution of individual process parameters.


![Tensile SHAP](assets/Tensile_SHAP_Beeswarm.png)


![Roughness SHAP](assets/Roughness_SHAP_Beeswarm.png)


---

# Global Sensitivity Analysis

Sobol sensitivity analysis was performed to quantify the influence of individual parameters and their interactions.


![Sensitivity](assets/Tensile_Sobol_ST_Bar.png)


---

# Multi-Objective Optimization

The NSGA-II optimization framework was applied to achieve a balanced trade-off between tensile strength improvement and surface roughness reduction.


![Pareto Front](assets/Fig1_Nominal_Pareto_Front.png)


---

# Robust Optimization and Decision Making

A robust optimization strategy incorporating uncertainty analysis and TOPSIS-based ranking was used to identify practical process conditions.


![Robust Optimization](assets/Fig2_Robust_Pareto_TOPSIS.png)


---

# Repository Structure
