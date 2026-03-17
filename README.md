# Polyphenol-Rich Dietary Patterns and Cardiovascular Risk in Older UK Adults

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

This repository contains the code, documentation, and reproducible analysis for investigating the association between polyphenol-rich dietary patterns and cardiovascular risk among older adults in the United Kingdom.

Polyphenols — bioactive compounds abundant in fruits, vegetables, tea, coffee, red wine, and certain grains — have been hypothesized to exert cardioprotective effects through antioxidant, anti-inflammatory, and vasodilatory mechanisms. This project examines whether adherence to polyphenol-rich dietary patterns is associated with lower cardiovascular risk markers (e.g., incident CVD events, blood pressure, lipid profile, arterial stiffness, or composite risk scores) in a population of older UK adults.

The analysis is designed to be fully reproducible and follows open science principles.

## Key Research Question

Is higher adherence to polyphenol-rich dietary patterns associated with reduced cardiovascular risk in older UK adults (aged 60+), independently of overall diet quality and established confounders?

## Data Source

- Secondary dataset: [Phenol explorer, USDA Flavonoid Database]
- Dietary assessment
- Cardiovascular outcomes: Hospital Episode Statistics (HES), primary care records, self-report, and/or biomarkers (e.g., SBP, DBP, HDL, LDL, CRP, PWV).
- Sample: Adults aged ≥60 years at baseline with complete dietary and CVD follow-up data (N ≈ XXX after exclusions).

**Note**: Raw data are not included in this repository due to data-sharing restrictions.

## Methods

- **Polyphenol intake estimation** — Using the Phenol-Explorer database (or USDA flavonoid database) matched to food items.
- **Dietary pattern derivation** — Principal Component Analysis (PCA) or cluster analysis to identify polyphenol-rich patterns (e.g., "fruit & vegetable", "tea & coffee", "wine & berries").
- **Cardiovascular risk assessment** — Cox proportional hazards models for incident events; linear/logistic regression for continuous/binary biomarkers.
- **Covariate adjustment** — Age, sex, BMI, smoking, physical activity, alcohol, socioeconomic position, total energy intake, and other dietary factors (e.g., Mediterranean diet score).
- **Sensitivity analyses** — Exclusion of early events, alternative polyphenol metrics, subgroup analyses (sex, BMI category, diabetes status).

All analyses are performed in Python

## Repository Structure
