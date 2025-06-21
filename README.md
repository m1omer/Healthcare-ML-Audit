# Healthcare-ML-Audit 

## Background 

The Project is based on a synthetic dataset from “Dissecting Racial Bias in an Algorithm Used to Manage the Health of Populations,” authored by Ziad Obermeyer, Brian Powers, Christine Vogeli, and Sendhil Mullainathan in Science Vol. 366, No. 6464 (2019). The research paper simulates Optum's propietary ImpactPro algorithm and highlights racial biases in the algorithm as it uses **future healthcare cost** as a proxy for **health need**. Due to systemic disparities black patients incur lower costs when it comes to healthcare. Thus, the algorithm overlooked them when identifying at risk individuals

This project reproduces and extends that analysis using the synthetic dataset modeled after the original research. We audit the logic of the algorithm, explore fairness metrics, and simulate interventions to reduce bias in real-world care decisions.


Dataset: https://gitlab.com/labsysmed/dissecting-bias

Research Paper: https://www.science.org/doi/10.1126/science.aax2342

