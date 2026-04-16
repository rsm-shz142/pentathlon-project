# Next Product to Buy Modeling (Pentathlon Project)

## Overview

This project develops customer-level predictive models to optimize promotional messaging strategies using experimental e-mail marketing data from the Pentathlon e-commerce platform.

The goal is to move from a one-size-fits-all approach to personalized marketing decisions that maximize long-term customer value.

---

## Background

A randomized controlled trial (RCT) tested different e-mail frequencies (1–4 per week). While higher frequency increased short-term revenue, it also significantly increased unsubscribe rates, negatively impacting long-term customer lifetime value (LTV).

This project builds on the experimental data to determine the most effective message (or no message) for each individual customer.

---

## Methodology

- Processed and engineered features using **Polars**
- Built predictive models including:
  - Logistic Regression (via `pyrsm`)
  - Random Forest
  - XGBoost
  - Neural Networks
- Applied the **Next Product to Buy (NPTB)** framework
- Estimated:
  - Purchase probability
  - Expected order value
  - Expected profit (assuming 60% COGS)
- Evaluated models using:
  - AUC
  - RMSE
  - Cross-validation
  - Gains curves

---

## Key Results

- Identified the optimal promotional message (or no message) for each customer
- Personalized targeting outperformed:
  - Uniform messaging strategies
  - Random message assignment
  - No-message baseline
- Achieved higher expected profit per customer through individualized decision-making

---

## Business Impact

- Improved marketing ROI through personalized messaging
- Reduced unsubscribe rates while maintaining revenue growth
- Enabled data-driven allocation of marketing resources
- Transformed A/B testing into a scalable personalization framework

---

## Files

- `pentathlon-project.ipynb`: Main notebook containing the full analysis

---

## Notes

This repository is a cleaned and simplified version of a course project for portfolio purposes. Some original data or materials may not be included.
