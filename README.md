# Silicon Materials Property Prediction

## Overview
A two-stage machine learning pipeline to predict electronic 
properties of silicon-containing materials using the 
Materials Project database.

## Pipeline
- Stage 1: Binary classifier (Random Forest) — Metal vs Non-metal
  - Accuracy: 93%
- Stage 2: Band gap regression (Gradient Boosting) — Non-metals only
  - R²: 0.825 | MAE: 0.550 eV

## Key Finding
Formation energy per atom is the strongest predictor of both 
metallic behavior and band gap magnitude — consistent with 
the physical relationship between chemical bonding strength 
and electronic structure in silicon compounds.

## Tools
Python | scikit-learn | pandas | SHAP | Materials Project API

## Data
1000 silicon-containing materials from Materials Project

## Status
🚧 In progress
