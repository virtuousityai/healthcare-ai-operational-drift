[![DOI](https://zenodo.org/badge/1176591665.svg)](https://doi.org/10.5281/zenodo.18919542)

# Operational Drift in Healthcare AI Agents

**Author:** Sathiyan Kutty  

This repository accompanies the research paper:

**Safe Model Migration for Healthcare Prior Authorization Agents: Operational Drift, Escalation Stability, and Compliance-Aware Evaluation**

## Overview

Healthcare organizations are increasingly deploying AI agents in administrative workflows such as:

- prior authorization
- clinical documentation
- medical coding

Model upgrades may introduce subtle behavioral changes that alter operational outcomes.

This research introduces two metrics for evaluating migration safety:

- **Operational Drift Score (ODS)**
- **Escalation Stability Score (ESS)**

## Repository Structure

paper/  
LaTeX source and compiled paper

figures/  
Architecture diagrams

scenarios/  
Synthetic clinical test cases

## Metrics

### Operational Drift Score

Measures workflow outcome differences between model versions.

### Escalation Stability Score

Measures consistency in human escalation routing.

## Purpose

This framework is intended to support healthcare organizations in evaluating AI model migrations in compliance-sensitive environments.

## Citation

See `CITATION.cff`.
