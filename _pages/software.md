---
title: "Software"
permalink: /software/
author_profile: false
---

## RandomMeas.jl

![Overview of RandomMeas.jl](/images/RandomMeas.png)
*Overview of the RandomMeas.jl workflow for randomized-measurement protocols.*

[RandomMeas.jl](https://github.com/bvermersch/RandomMeas.jl/) is an open-source Julia package for end-to-end randomized-measurement experiments: generating measurement settings, loading or simulating measurement outcomes, constructing classical shadows, and estimating physical properties of quantum states and processes. It is designed to be modular and extensible, with applications ranging from theoretical studies to the analysis of experimental quantum-device data. The package builds on [ITensors.jl](https://itensor.github.io/ITensors.jl/) for tensor-network simulation and post-processing and is developed together [Benoît Vermersch](https://bvermersch.github.io/).

**Install**

```julia
julia> ]
pkg> add RandomMeas
```

**Features**

RandomMeas.jl includes tools for:

- randomized measurement settings,
- classical-shadow estimators,
- expectation values, fidelities, entanglement measures, and process metrics,
- robust and shallow shadow techniques,
- batch estimators,
- statistical uncertainty estimation,
- tensor-network simulation and benchmarking workflows.

**Worked examples**

Selected Jupyter notebooks from the [examples directory](https://github.com/bvermersch/RandomMeas.jl/tree/main/examples):

- [Cross-platform verification](https://github.com/bvermersch/RandomMeas.jl/blob/main/examples/CrossPlatform.ipynb)
- [Analyzing the experimental data of Brydges et al., *Science* (2019)](https://github.com/bvermersch/RandomMeas.jl/blob/main/examples/BrydgesScience2019.ipynb)
- [Robust shadow tomography](https://github.com/bvermersch/RandomMeas.jl/blob/main/examples/RobustShadowTomography.ipynb)
- [Cross-entropy benchmarking](https://github.com/bvermersch/RandomMeas.jl/blob/main/examples/CrossEntropyBenchmarking.ipynb)
- [Running randomized measurements on IBM Qiskit](https://github.com/bvermersch/RandomMeas.jl/blob/main/examples/RandomizedMeasurementsQiskit.ipynb)

**Links**

- [GitHub repository](https://github.com/bvermersch/RandomMeas.jl/)
- [Documentation](https://bvermersch.github.io/RandomMeas.jl/dev/)
- [Quantum paper](https://quantum-journal.org/papers/q-2026-04-28-2086/) ([arXiv:2509.12749](https://arxiv.org/abs/2509.12749))

**License:** Apache-2.0.

**Reference**

Andreas Elben and Benoît Vermersch, *RandomMeas.jl: A Julia Package for Randomized Measurements in Quantum Devices*, *Quantum* **10**, 2086 (2026).
