# 📡 MRI-Knowledge-Distillation

<div align="center">

[![Status](https://img.shields.io/badge/Status-Published%20%26%20Peer%20Reviewed-brightgreen?style=for-the-badge)]()
[![Journal](https://img.shields.io/badge/Journal-MDPI%20Sensors-blue?style=for-the-badge)]()
[![Python](https://img.shields.io/badge/Python-3.8%2B-blueviolet?style=for-the-badge&logo=python&logoColor=white)]()
[![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-ee4c2c?style=for-the-badge&logo=pytorch&logoColor=white)]()
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)]()

*Official implementation, experimentation code, and evaluation frameworks for multi-objective, privacy-preserving radar-only rehabilitation monitoring utilizing advanced knowledge distillation techniques.*

</div>

---

## 🌟 Introduction & Research Context

Modern health and rehabilitation monitoring demands high-precision tracking while strictly preserving patient privacy. Traditional vision-based systems present significant privacy concerns, whereas cumbersome wearable sensors can restrict natural movement. 

This repository accompanies the peer-reviewed research study: **"Multi-Objective Evaluation of Wearable-Assisted Radar-Only Rehabilitation Monitoring"** (published in *MDPI Sensors*). By integrating **Relational Knowledge Distillation (RKD)** and **constrained multi-objective optimization (Pareto-optimal formulations)**, this project bridges the gap between resource-intensive teacher networks and ultra-lightweight, deployment-ready student models for non-invasive health monitoring.

---

## 🏗️ Repository Architecture

```text
MRI-Knowledge-Distillation/
├── FINAL CODES/                      # Production-ready scripts and end-to-end pipelines
├── Fifth Constrained Code/           # Advanced constraint-aware training & regularization modules
├── First Code & Output/              # Foundational baseline experimentation logs & outputs
├── Second Code & Output/             # Intermediate model iterations & feature extraction loops
├── Third Code/                       # Specialized model components & architectural tuning scripts
├── Reviewer_R1_Experiments_Notebooks/# Supplementary peer-review validation & robustness checks
├── Aurora-RKD-MRI-Novel.ipynb        # Novel Aurora Relational Knowledge Distillation implementation
├── Constrained-RTPD-Novel.ipynb      # Constrained Radar-Target-Person Distillation (RTPD) workflows
├── Pareto-RKD-MRI-novel.ipynb        # Multi-objective Pareto-optimal RKD experimentation
├── RTPD-NET-MRI-Novel.ipynb          # End-to-end RTPD-NET architecture & training notebook
├── Multi_Objective_Evaluation...pdf  # Full research manuscript
└── Acceptance-Certificate...pdf      # Official publication acceptance documentation
