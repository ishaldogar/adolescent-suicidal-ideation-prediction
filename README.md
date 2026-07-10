# Adolescent Suicidal Ideation Prediction: Integrating Statistical and Machine Learning Approaches

NSF-funded undergraduate research (Texas State University REU) predicting suicidal
ideation among Korean-Chinese adolescents in Northeast China using a dual-method
design combining inferential statistics and machine learning.

🏆 **Awarded "Most Significant Contribution to the Field of Study"** — Texas State
FCS in Bloom Conference, April 2026

📄 **[View the research poster](./poster.pdf)**

## Overview

Suicide remains a leading cause of death for adolescents globally, and evidence on
risk factors for ethnic-minority youth in the Majority World is limited. This study
examined behavioral predictors of suicidal ideation in N=267 Korean-Chinese
adolescents from bilingual secondary schools, framed by the diathesis-stress model.

## Methods

**Dual-method approach:**
1. **Inferential statistics** — Binary logistic regression (IBM SPSS) to identify
   significant behavioral risk factors from survey measures
2. **Machine learning** — Predictive classification model (Python, pandas,
   scikit-learn) with a 70/30 train-test split, optimized for sensitivity in a
   risk-screening context

## Key Findings

- **Despair** was the strongest predictor of suicidal ideation (OR = 2.16, p < .001)
- **Parent-child conflict** (OR = 1.72) and **gender-based peer teasing** (OR = 1.67)
  significantly elevated risk
- **Parental promotion of mistrust** unexpectedly emerged as a protective factor
  (OR = 0.40), suggesting population-specific effects among Asian youth
- The ML model achieved **64% recall** on the at-risk class despite 4:1 class
  imbalance — prioritizing sensitivity, since false negatives carry far higher cost
  than false positives in screening applications

## Data & Code Availability

The dataset and analysis code are not publicly available due to human-subjects
research protections.

## Authors

Ishal Dogar (Austin Community College), Kaitlyn Rubio, Yishan Shen (School of Family
and Consumer Sciences, Texas State University)

*Supported by the National Science Foundation and Texas State University.*
