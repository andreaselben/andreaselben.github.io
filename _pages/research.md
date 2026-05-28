---
title: "Research"
permalink: /research/
author_profile: false
---

How can we understand, learn from, and ultimately use quantum devices as controllable quantum many-body systems?

Quantum technology is moving toward increasingly capable devices for quantum computation, simulation, and sensing. Already today, these devices provide unprecedented experimental access to controlled many-body quantum systems, with tunable dynamics, measurements, interactions, and noise.

These devices are fascinating quantum many-body systems in their own right. We develop theoretical and computational approaches to understand, probe, and learn from them — and to turn this understanding into useful protocols for quantum simulation, benchmarking, and quantum computation.

## Scientific directions

### Probing and learning quantum many-body systems

*How can we extract reliable information about quantum states, processes, and many-body phenomena from limited, noisy measurement data?*

Modern quantum devices give experimental access to wavefunctions, entanglement, correlations, and noise channels in ways that were not previously available. We develop methods to turn this access into useful physical information — with randomized measurements, classical shadows, robust estimators, and tensor-network post-processing playing a central role. Current directions include learning of quantum states and processes, sample-efficient measurement design, classical-shadow protocols for non-linear properties, and the open-source [RandomMeas.jl](/software/) library.

*Selected publications:*
[Probing entanglement entropy via randomized measurements](https://arxiv.org/abs/1806.05747) (Science 2019) ·
[The randomized measurement toolbox](https://arxiv.org/abs/2203.11374) (Nat. Rev. Phys. 2023) ·
[Optimal randomized measurements for a family of non-linear quantum properties](https://arxiv.org/abs/2505.09206) (PRX Quantum 2026).

### Benchmarking and validating quantum devices

*How can we tell what a quantum device has actually done, especially when its target is too large to simulate classically?*

As quantum devices grow in size and complexity, standard validation methods become insufficient. We design benchmarking protocols that connect experimentally accessible data to physically meaningful diagnostics of performance — operating in regimes where direct classical simulation is no longer feasible. Current directions include cross-entropy and many-body benchmarks, quantum-classical and cross-device fidelity estimation, and the learning of structured and non-Markovian noise.

*Selected publications:*
[Cross-platform verification of intermediate-scale quantum devices](https://arxiv.org/abs/1909.01282) (PRL 2020) ·
[Benchmarking highly entangled states on a 60-atom analog quantum simulator](https://arxiv.org/abs/2308.07914) (Nature 2024) ·
[Thermalization and criticality on an analog–digital quantum simulator](https://arxiv.org/abs/2405.17385) (Nature 2025) ·
[Efficiently learning non-Markovian noise in many-body quantum simulators](https://arxiv.org/abs/2511.16772) (2025).

### Quantum simulation and many-body dynamics

*How can quantum devices be used to simulate many-body dynamics in regimes where classical methods become unreliable or prohibitively costly?*

We study quantum devices as platforms for exploring and simulating quantum many-body dynamics, with particular emphasis on digital–analog approaches and hybrid qubit–boson architectures. These combine the hardware efficiency of analog evolution with the flexibility of digital control, opening routes toward simulation of strongly correlated matter and quantum molecular dynamics. Current directions include thermalization and emergent randomness in projected state ensembles, hybrid qubit–boson devices, and quantifying the classical hardness of analog simulation — testing experimentally where quantum simulators provide information that is hard to obtain classically.

*Selected publications:*
[Learning conservation laws in unknown quantum dynamics](https://arxiv.org/abs/2309.00774) (PRX Quantum 2024) ·
[A maximum entropy principle in deep thermalization and Hilbert-space ergodicity](https://arxiv.org/abs/2403.11970) (PRX 2024) ·
[Bosonic entanglement and quantum sensing from energy transfer in two-tone Floquet systems](https://arxiv.org/abs/2410.11158) (PRR 2025).


## Methods

Our work combines analytical and numerical approaches from quantum information theory, many-body physics, statistical learning, and computational physics.

*Analytical theory.* Tools from quantum information theory and classical statistics, used to design protocols, derive estimators, and quantify sample complexity and robustness to noise.

*Simulation and post-processing.* State-vector and density-matrix simulations, quantum-trajectory methods, tensor-network approaches, and Pauli-path or local-information algorithms for many-body quantum dynamics.

*From theory to data and open-source software.* Connecting theoretical guarantees with practical tools — randomized-measurement and classical-shadow protocols, scalable estimator design, uncertainty quantification, error mitigation, and the [RandomMeas.jl](/software/) Julia package.
