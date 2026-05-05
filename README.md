# Awesome-Neuron

## Multi-Scale Simulation Platforms for Biological Neurons Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Modeling Molecular and Cellular Behavior in Neurons*  
**Last updated: March 2026**

This repository tracks notable **platforms** and **open-source projects** for **multi-scale simulation** of biological neurons — tools that model processes across molecular (ion channels, synapses, biochemical signaling), subcellular, single-cell, and network/tissue scales. These simulators support compartmental modeling, stochastic simulation, reaction-diffusion, electrophysiology, and large-scale network simulations for computational neuroscience research.

**Examples** include NEURON Simulator, CoreNEURON, MOOSE, STEPS, Arbor, NetPyNE, Open Source Brain (OSB), and ModelDB (the category leaders). Tools listed here emphasize **multi-scale capabilities** (molecular to circuit level), spatial stochastic modeling, parallel computing, and integration with experimental data.

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, customization, local execution, and full transparency — ideal for researchers building, extending, or reproducing neuronal simulations.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS / Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS / Hosted Platforms

### Core Multi-Scale Neuronal Simulation Platforms

- **[NEURON Simulator](https://nrn.readthedocs.io/)**  
  Gold-standard simulator for detailed biophysical models of neurons and networks. Supports compartmental modeling, stochastic channels, parallel simulation, and integration with Python.

- **[CoreNEURON](https://nrn.readthedocs.io/)** (integrated in NEURON)  
  Optimized engine for large-scale network simulations, delivering significant performance improvements on modern hardware.

### Advanced & Specialized Platforms

- **[MOOSE (Multiscale Object-Oriented Simulation Environment)](https://moose.ncbs.res.in/)**  
  Multi-scale simulator for neural systems ranging from biochemical signaling to complex neuronal networks and circuits.

- **[STEPS (STochastic Engine for Pathway Simulation)](https://steps.sourceforge.net/)**  
  Exact stochastic simulator for reaction-diffusion systems in complex 3D neuronal geometries.

- **[Arbor](https://arbor-sim.org/)**  
  High-performance, multi-compartment neural network simulation library designed for modern hardware and scalability.

- **[NetPyNE](https://www.netpyne.org/)**  
  Python package for developing, simulating, and analyzing large-scale biological neuronal networks using NEURON.

- **[Open Source Brain (OSB)](https://www.opensourcebrain.org/)**  
  Collaborative platform for sharing, visualizing, and simulating neuronal models in standardized formats (NeuroML).

**Other notable mentions**: ModelDB (model repository), Brian 2, NEST, and various hybrid tools.

## Open-Source GitHub Projects

### Dedicated Multi-Scale Neuronal Simulation Projects

- **[NEURON Simulator](https://github.com/neuronsimulator/nrn)**  
  The leading open-source simulator for biologically detailed neuron and network models. Supports Hodgkin-Huxley style compartmental modeling, reaction-diffusion, and Python scripting.

- **[CoreNEURON](https://github.com/neuronsimulator/nrn/tree/master/src/coreneuron)** (integrated in NEURON)  
  High-performance compute engine optimized for large-scale parallel simulations of detailed neuronal networks.

- **[MOOSE (BhallaLab)](https://github.com/BhallaLab/moose)**  
  Multiscale Object-Oriented Simulation Environment for modeling from biochemical signaling pathways to full neuronal networks and circuits.

- **[STEPS](https://github.com/CNS-OIST/STEPS)**  
  STochastic Engine for Pathway Simulation — supports exact stochastic simulation of reaction-diffusion systems in complex 3D cellular geometries.

- **[Arbor](https://github.com/arbor-sim/arbor)**  
  Modern, performance-portable library for multi-compartment neuron network simulations. Designed for scalability on CPUs and accelerators.

- **[NetPyNE](https://github.com/suny-downstate-medical-center/netpyne)**  
  High-level Python interface for NEURON. Simplifies development, parallel simulation, optimization, and analysis of large-scale neuronal networks.

- **[Open Source Brain (OSB)](https://github.com/OpenSourceBrain)**  
  Platform and tools for sharing, simulating, and collaborating on neuronal models, with strong support for NeuroML standards.

- **[ModelDB](https://modeldb.yale.edu/)** (Yale)  
  Curated repository of published computational neuroscience models, many compatible with NEURON, MOOSE, and other simulators.

### Additional Strong Open-Source Options

- **[Brian 2](https://github.com/brian-team/brian2)** — Flexible Python simulator for spiking neural networks with emphasis on ease of use.
- **[NEST Simulator](https://github.com/nest/nest-simulator)** — Leading simulator for large-scale spiking neural networks.
- **[NeuroML](https://github.com/NeuroML)** and related tools — Standard for describing and exchanging multi-scale neuronal models.
- **PhysiCell** (for hybrid neuro-biological modeling) and extensions of MOOSE/STEPS.
- Visualization and analysis tools: NEURON GUI, NetPyNE-UI, OSB visualization platforms.

**Frameworks for building custom simulations**: Combine core engines (NEURON/Arbor) with Python interfaces (NetPyNE), NeuroML standards, and parallel computing tools for multi-scale neuronal modeling.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Simulation accuracy depends on model parameters, validation against experimental data, and appropriate numerical methods. Always verify results biologically and numerically.
- For research publications, cite the original tool papers and ensure compliance with licenses.

---

**Made for computational neuroscientists, systems biologists, and neuroscience researchers.**  
Let's make multi-scale neuronal modeling more accessible, reproducible, and collaborative.



## Star History

<a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-Neuron&type=date&legend=bottom-right">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Neuron&type=date&theme=dark&legend=bottom-right" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Neuron&type=date&legend=bottom-right" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Neuron&type=date&legend=bottom-right" />
 </picture>
</a>
