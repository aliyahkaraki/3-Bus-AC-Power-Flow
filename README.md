# 3-Bus-AC-Power-Flow
Newton–Raphson AC power flow analysis of a 3-bus electrical network in Python.

Python implementation of a Newton–Raphson AC load-flow analysis for a three-bus electrical network.

The model calculates bus voltage magnitudes and angles, line power flows and network losses. It also compares a base-load case with increased demand and distributed solar generation.

## Key Results

- **Base case:** Bus 3 voltage = 0.9738 pu, losses = 2.24 MW
- **High demand:** Bus 3 voltage = 0.9672 pu, losses = 2.91 MW
- **20 MW solar:** Bus 3 voltage = 0.9821 pu, losses = 1.67 MW

## Tools

- Python
- NumPy
- Matplotlib

## Key Findings

Increasing demand reduced the Bus 3 voltage and increased network losses. Adding 20 MW of distributed solar improved the voltage profile and reduced losses by decreasing the amount of real power transferred through the network.
