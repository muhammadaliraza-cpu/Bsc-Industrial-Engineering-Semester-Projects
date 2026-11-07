# Exploring Big Data in Quality Control of SMEs

A Design of Experiments (DOE) course project exploring data-driven quality control in manufacturing.

## Project Overview

This project developed a four-stage analytics framework to support quality control in **Small and Medium Enterprises (SMEs)**.

The study explored defect severity classification, associations between defects and process factors, rework prediction, and the estimated effects of selected quality-related factors.

## Project Objectives

- Classify defects as minor, moderate, or major.
- Identify associations supporting investigation of potential defect causes.
- Predict rework costs and labor requirements.
- Explore the effects of process factors on quality outcomes.
- Support corrective-action and resource-allocation decisions.

## Analytics Framework

| Stage | Method | Purpose |
|---|---|---|
| Defect classification | Multilayer Perceptron (MLP) | Predict defect severity |
| Root cause exploration | Apriori association rule mining | Identify patterns linking process factors and defects |
| Rework prediction | Regression modeling | Estimate rework costs and labor requirements |
| Causal analysis | Propensity Score Matching (PSM) | Estimate effects through matched comparisons |

## Dataset and Preparation

The report describes a publicly available **Kaggle manufacturing quality dataset** containing:

- Fabric strength
- Color fastness
- Seam integrity
- Fit accuracy

Preparation included addressing missing or inconsistent values, encoding and scaling variables, and examining outliers.

The classification workflow used an **80:20 training-validation split**.

## Analysis Performed

- Trained an MLP to classify defect severity.
- Evaluated association rules using support, confidence, and lift.
- Applied regression models to predict rework requirements.
- Used PSM to compare observations with similar measured characteristics.
- Estimated Average Treatment Effects (ATEs) for selected factors and quality outcomes.

## Reported Results

| Analysis | Result Reported in the Project |
|---|---|
| Defect classification | 92% accuracy |
| Rework prediction | R-squared of 0.87 |
| Poor material quality and major defects | 85% rule confidence; lift of 3.2 |
| Improper dyeing and moderate defects | 78% rule confidence; lift of 2.5 |
| PSM analysis | Estimated effects on fabric strength and fit accuracy |

## Quality Engineering Applications

The framework was intended to help SMEs prioritize defects, investigate process issues, estimate rework resources, and evaluate potential quality improvements.

## Methods and Skills

- Manufacturing Quality Analysis
- Data Cleaning and Feature Preparation
- Multilayer Perceptron Classification
- Association Rule Mining
- Regression Modeling
- Propensity Score Matching
- Average Treatment Effect Estimation

## Academic Information

**Course:** Design of Experiments (DOE)  
**Institution:** University of Engineering and Technology, Taxila  
**Program:** BSc Industrial Engineering  
**Submitted to:** Dr. Khurram Ali

**Project Team:**

- Qudrat Ullah — 21-IE-01
- Muhammad Ali Raza — 21-IE-21
