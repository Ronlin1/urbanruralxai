# urbanruralxai

🌍 Urban–Rural Energy Disparities: An XAI Approach to Biomass Allocation
A comprehensive machine learning framework for predicting district-level biomass energy potential in Uganda using Explainable AI (XAI), advanced modeling techniques, and MLOps best practices.
This research addresses urban–rural energy gaps by generating transparent insights and data-driven policy recommendations.

📊 Overview
This project introduces an end-to-end workflow combining:

Machine Learning

Explainable AI

Geospatial features

Model interpretability

Policy scenario simulation

MLOps experiment tracking

The system predicts biomass energy potential across Uganda’s districts and identifies the factors driving persistent urban–rural disparities. It also enables policymakers to simulate conservation and afforestation interventions for equitable biomass allocation planning.

🚀 Key Features
🔹 Eight Machine Learning Models Evaluated
LightGBM

XGBoost

Random Forest

CatBoost

Gradient Boosting

Extra Trees

TabTransformer

Graph Attention Network (GAT)

🔹 Comprehensive Explainable AI (XAI) Suite
SHAP – global & local feature importance

LIME – instance-level explanations

GradientSHAP / Integrated Gradients – deep learning interpretability

Attention Visualization (for GAT)

🔹 Robust MLOps Pipeline
Experiment tracking using MLflow

Versioned artifacts (models, metrics, parameters)

Reproducible pipelines with conda/Docker environments

🔹 Policy Simulation Engine
Simulates the effect of:

Afforestation interventions

Reduced hardwood loss

Combined conservation strategies

Produces quantitative impacts in GJ at both national and district levels.

🔹 Full Deployment Support
Dockerized model

Flask API

CI/CD-ready for Render / Heroku containers

🎯 Key Findings
⭐ Best Performing Model
LightGBM

R² = 0.535 (in log-transformed space)

Most stable and well-generalized across districts

⭐ Most Influential Feature
Hardwood biomass stock

Dominant driver across SHAP and LIME analyses

⭐ Policy Simulation Insights
A combined afforestation + conservation strategy could increase national biomass energy potential by
≈ 11.5 million GJ annually

⭐ Regional Patterns
Central and Western Uganda display the highest predicted biomass potential

Districts with rapidly declining hardwood stock show high vulnerability

