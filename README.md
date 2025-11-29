# urbanruralxai

Urban-Rural Energy Disparities: An XAI Approach to Biomass Allocation
https://img.shields.io/badge/python-3.8+-blue.svg
https://img.shields.io/badge/License-MIT-yellow.svg
https://img.shields.io/badge/MLflow-1.0+-orange.svg
https://img.shields.io/badge/Explainable-AI-green.svg

A comprehensive machine learning framework for predicting district-level biomass energy potential in Uganda using Explainable AI (XAI) and MLOps practices. This research addresses urban-rural energy disparities through data-driven policy recommendations.

📊 Overview
This project presents an end-to-end framework that leverages machine learning and Explainable AI to predict and understand the drivers of biomass energy potential in Uganda. The framework enables policymakers to simulate the impact of various intervention strategies and make evidence-based decisions for equitable resource allocation.

Key Features
8 ML Models Evaluated: LightGBM, XGBoost, Random Forest, CatBoost, Gradient Boosting, Extra Trees, TabTransformer, GAT

Comprehensive XAI Analysis: SHAP, LIME, GradientSHAP for model interpretability

Robust MLOps Pipeline: MLflow for experiment tracking and reproducibility

Policy Simulation Tool: Quantify impact of afforestation and conservation policies

Full CI/CD Deployment: Dockerized Flask API deployable on Render/Heroku

🎯 Key Findings
Best Performing Model: LightGBM (R² = 0.535 in log space)

Most Important Feature: Hardwood biomass (identified via SHAP analysis)

Policy Impact: Combined afforestation + conservation policy could increase national energy potential by 11.5 million GJ annually

Regional Insights: Central and Western Uganda show highest energy potential
