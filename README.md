Machine Learning Assisted Multi-Objective Optimization of ABS--Glass Fiber FDM Process Parameters

Project Overview

This repository presents a comprehensive machine learning-driven
framework for predicting, interpreting, and optimizing ABS--glass fiber
reinforced Fused Deposition Modeling (FDM) additive manufacturing
processes.

The framework integrates experimental data analysis, design-space
exploration, virtual design of experiments, machine learning surrogate
modeling, explainable artificial intelligence (XAI), global sensitivity
analysis, uncertainty evaluation, and NSGA-II based multi-objective
optimization.

The objective of this research is to develop an interpretable
AI-assisted manufacturing framework capable of improving tensile
strength while reducing surface roughness through data-driven process
optimization.

Research Objectives

Develop predictive models for tensile strength and surface
roughness.

Compare multiple machine learning algorithms for FDM performance
prediction.

Identify dominant process parameters using explainable AI.

Quantify parameter influence through Sobol sensitivity analysis.

Optimize printing conditions using NSGA-II multi-objective
optimization.

Identify robust process windows considering uncertainty.

Research Workflow

Experimental Data
↓
Data Processing and Analysis
↓
Design Space Exploration
↓
Virtual DOE Generation
↓
Machine Learning Modeling
↓
Model Validation
↓
Explainable AI Analysis
↓
Sensitivity Analysis
↓
NSGA-II Optimization
↓
Robust Parameter Selection

Input Parameters

The framework considers:

Glass fiber content

Infill density

Layer thickness

Nozzle temperature

Bed temperature

Printing speed

Output Responses

Tensile strength (MPa)

Surface roughness (µm)

Design Space Exploration

The design space was evaluated to ensure effective coverage of the FDM
processing region before machine learning development.



Dataset Validation

Real and virtual response distributions were compared to verify
statistical consistency.







Machine Learning Framework

Multiple algorithms were evaluated:

XGBoost

LightGBM

CatBoost

Random Forest

Extra Trees

Gradient Boosting

Support Vector Regression

Neural Network

Model performance was assessed through validation and comparative
analysis.





Prediction Performance

Tensile Strength Prediction



Surface Roughness Prediction



Explainable Artificial Intelligence

SHAP analysis was applied to interpret model decisions and identify
important manufacturing parameters.





Global Sensitivity Analysis

Sobol analysis was performed to quantify parameter contribution and
interaction effects.





Multi-Objective Optimization

NSGA-II was applied to solve the conflicting objectives:

Maximize tensile strength

Minimize surface roughness



Robust Optimization and Decision Support

Uncertainty-aware optimization and TOPSIS-based ranking were used to
identify practical solutions.





Research Contributions

This project provides an integrated framework combining:

Machine learning prediction

Explainable AI

Sensitivity analysis

Uncertainty assessment

Multi-objective optimization

The proposed approach supports transparent and data-driven decision
making for advanced additive manufacturing process design.

Repository Structure

Code      - Jupyter notebooks
Data      - Experimental and generated datasets
Results   - Analysis outputs and figures
Assets    - Publication-quality images

Technologies Used

Python, NumPy, Pandas, Scikit-learn, XGBoost, LightGBM, CatBoost, SHAP,
SALib, PyMOO, Matplotlib

Author

Apurbo Das

Research Project: Machine Learning Assisted Multi-Objective Optimization
of ABS--Glass Fiber FDM Process Parameters
