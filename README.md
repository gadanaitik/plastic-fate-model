# Multicompartment Plastic Fate Model

## Overview

Plastic pollution has emerged as one of the most significant environmental challenges of the 21st century. Once released into the environment, plastics can be transported between multiple interconnected environmental compartments including surface waters, sediments, soils, the atmosphere, and biological systems. Understanding the long-term fate of plastics requires a systems-level approach that accounts for transport processes, degradation mechanisms, and compartment interactions.

This project develops a **multicompartment plastic fate model** to investigate the transport, accumulation, and persistence of plastics across environmental compartments. The model is designed as a mechanistic mass-balance framework that tracks plastic stocks and flows over time and evaluates how environmental processes influence long-term plastic distribution.

This repository was developed as an independent research project in support of research interests in environmental modeling, uncertainty quantification, and sustainability science.

---

## Research Motivation

Many studies focus on plastic concentrations within a single environmental compartment. However, plastics do not remain stationary after entering the environment.

For example:

- Plastics entering rivers may be transported to oceans.
- Plastics in surface waters may settle into sediments.
- Plastics may fragment into smaller particles through degradation.
- Atmospheric transport can redistribute particles over large distances.
- Biological uptake can temporarily store plastics within ecosystems.

Because these processes are interconnected, compartment-specific analyses often fail to capture the complete environmental fate of plastic materials.

The goal of this work is to develop a reproducible modeling framework that enables analysis of:

1. Transport pathways between environmental compartments.
2. Long-term accumulation patterns.
3. Key drivers of plastic persistence.
4. Model sensitivity to uncertain parameters.
5. The effect of uncertainty on model predictions.

---

## Research Questions

This project seeks to address the following questions:

### Primary Questions

1. How does plastic move between environmental compartments over time?
2. Which environmental compartments act as long-term sinks for plastic accumulation?
3. What processes contribute most strongly to plastic persistence?
4. Which model parameters exert the greatest influence on predicted outcomes?
5. How sensitive are model conclusions to assumptions?

---

## Repository Structure:
The repository is organized to promote reproducibility, transparency, and future extensibility of the model.

### notebooks/
`Multi-Compartment Plastic Fate Model.ipynb`: Serves as the central implementation python notebook of the model. Data is simulated and generated within the notebook along with detailed explanations of the assumptions and easy-to-follow code and markdown cells.

### requirements.txt
Lists all Python dependencies required to reproduce the model and analyses. 
