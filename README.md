# DES

Public code and data repository for our study on screening deep eutectic solvent formulations with molecular simulation.

## About

This repository contains the computational workflow and results behind the paper. The workflow covers candidate preparation, simulation setup and execution, enhanced sampling, and free-energy analysis with MBAR diagnostics. Results include screening scores for candidate formulations and reference free-energy calculations.

## Contents

- `DES_method/` — workflow code, input data, parameters, and examples
  - `code/` — Python modules for preparation, simulation, sampling, screening, and MBAR diagnostics
  - `inputs/` — candidate, component, formulation, and composition data
  - `parameters/` — alchemical lambda schedules, model settings, and simulation protocols
  - `examples/` — small example inputs with expected outputs
  - `run.py` — entry point driving the workflow
  - `environment.yml` — conda environment specification
- `DES_results/` — reported screening scores, free-energy results, and water reference data, plus data sources

## Status

The files in this repository are currently placeholders. Full code and data will be released here upon publication of the associated paper.

## Reproduce

Create the conda environment from `environment.yml`, then run the workflow with `run.py`. See `examples/` for a minimal illustration.
