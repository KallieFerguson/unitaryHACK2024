---
title: "QuantumToolbox.jl"
emoji: 
project_url: https://github.com/albertomercurio/QuantumToolbox.jl
metaDescription: Julia Package for Quantum Optics and Quantum Physics
date: 2024-04-01
summary: Julia Package for Quantum Optics and Quantum Physics
tags:
  - lindblad
  - optics
  - julia
bounties:
  - TBD
---

# QuantumToolbox

| [![Dev](/src/assets/img/docs-dev-blue.svg)](https://albertomercurio.github.io/QuantumToolbox.jl/dev) | [![Stable](/src/assets/img/docs-stable-blue.svg)](https://albertomercurio.github.io/QuantumToolbox.jl/stable) | [![Build-Status](/src/assets/img/build-status.svg)](https://github.com/albertomercurio/QuantumToolbox.jl/actions/workflows/CI.yml?query=branch%3Amain) | [![Coverage](/src/assets/img/coverage.svg)](https://codecov.io/gh/albertomercurio/QuantumToolbox.jl) | [![DOI](/src/assets/img/DOI.svg)](https://doi.org/10.5281/zenodo.10822817) |
|-----|--------|-------|----------|-----|


## Introduction

[QuantumToolbox.jl](https://github.com/albertomercurio/QuantumToolbox.jl) is a cutting-edge Julia package designed for quantum physics simulations, closely emulating the popular Python [QuTiP](https://github.com/qutip/qutip) package. It uniquely combines the simplicity and power of Julia with advanced features like GPU acceleration and distributed computing, making simulation of quantum systems more accessible and efficient.

## Features

QuantumToolbox.jl is equipped with a robust set of features:

- **Quantum State and Operator Manipulation:** Easily handle quantum states and operators with a rich set of tools.

- **Dynamical Evolution:** Advanced solvers for time evolution of quantum systems.

- **Measurement and Statistics:** Comprehensive quantum measurement simulation and analysis.

- **GPU and Distributed Computing:** Leverage GPU and distributed resources for high-performance computing.

## Installation

```julia
using Pkg

Pkg.add("QuantumToolbox")
```