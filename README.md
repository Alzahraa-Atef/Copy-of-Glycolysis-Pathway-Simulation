# Glycolysis Pathway Simulation with Inhibitor

## Description
This project simulates the glycolysis metabolic pathway using **ordinary differential equations (ODEs)**. It models the effect of an inhibitor on one of the key enzymatic steps and shows how metabolite concentrations change over time.

Metabolites included:  
- Glucose (Glc)  
- Glucose-6-phosphate (G6P)  
- Fructose-6-phosphate (F6P)  
- Fructose-1,6-bisphosphate (FBP)  
- Glyceraldehyde-3-phosphate (GAP)  
- Pyruvate (Pyr)  

## Features
- Simulation using `scipy.integrate.solve_ivp`  
- Inhibitor effect modeled with an IC50-based formula  
- Plots of metabolite concentrations over time using `matplotlib`  
- Easy to modify rate constants, initial conditions, and inhibitor concentrations  

## Requirements
- Python >= 3.8  
- numpy  
- scipy  
- matplotlib  

Install dependencies via pip:

```bash
pip install numpy scipy matplotlib
