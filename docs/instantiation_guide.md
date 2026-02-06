# CMF-DIAMOND Instantiation Guide

## Overview
CMF-DIAMOND is designed for direct instantiation within AI systems. 
This guide explains how to load the tool and evaluate organizational psi-states.

## Step 1 — Load the JSON
Provide the cmf_diamond_tool.json file to the AI system as a structured artifact.

## Step 2 — Provide Organizational Inputs
Inputs must include:
- Processes
- Structure
- Strategy
- People

These are mapped to:
psi = (M_e, M_c, M_a, M_s)

## Step 3 — Run Operations
### reflect_state
Maps inputs to mirror coordinates.

### calculate_resonance
Computes:
- Coherence C(psi)
- Tension V(psi)
- Local curvature
- Stability class

### simulate_shift
Predicts:
- psi(t+1)
- Shift vector
- Basin of attraction

## Step 4 — Interpret Results
High coherence = stability
High tension = misalignment
Shift vector = predicted organizational change

## Example
See docs/examples/sample_input.json
