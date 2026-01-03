# Minimal Hemispheric Asymmetry Model for Self-Agency

This repository contains the complete Python code used to generate all analyses and figures reported in the manuscript:

**"Hemispheric asymmetry is a necessary condition for self-agency during active movement."**

## Contents

- `analysis.py`  
  Full implementation of the model, simulations, and analyses used in the paper.

The code reproduces:
- Agency variable time series (Figure 3A)
- Distribution of the agency variable (Figure 3B)
- Temporal stability index (Figure 3C-1)
- Attribution consistency (Figure 3C-2)

No external datasets are required.

## Requirements

- Python 3.9+
- NumPy
- Matplotlib

## Usage

Run the analysis script:

```bash
python analysis.py

This will reproduce all results and figures reported in the manuscript using fixed random seeds.

Notes

The right-hemisphere model is strictly action-agnostic and has no access to motor commands.

Hemispheric asymmetry is implemented solely through information access and temporal integration constants.

All parameters correspond exactly to those described in the Methods section of the manuscript.
