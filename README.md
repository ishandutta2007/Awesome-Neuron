<div align="center">

# 🧠 Awesome-Neuron: Computational Neuroscience & Brain Simulation 🔬

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Stars](https://img.shields.io/github/stars/ishandutta2007/Awesome-Neuron?style=social)](https://github.com/ishandutta2007/Awesome-Neuron/stargazers)

**A curated list of multi-scale simulation platforms, SaaS products, and open-source projects for biological neurons and neural circuits.**

[Explore Platforms](#saas--hosted-platforms) • [Open Source Projects](#open-source-github-projects) • [Contribute](#how-to-contribute)

---

![Neuroscience Banner](https://images.unsplash.com/photo-1675191475052-dc335a91b29e?auto=format&fit=crop&w=1200&h=400&q=80)

</div>

## 🌟 Overview

Welcome to **Awesome-Neuron**, the definitive ecosystem for **computational neuroscience** and **brain simulation**. This repository tracks notable **multi-scale simulation platforms** — tools that model processes across molecular (ion channels, synapses, biochemical signaling), subcellular, single-cell, and network/tissue scales.

Whether you are interested in **stochastic simulation**, **reaction-diffusion systems**, or **large-scale spiking neural networks**, this list covers the gold-standard tools used by researchers worldwide.

> **Focus Area**: Multi-scale capabilities (molecular to circuit level), spatial stochastic modeling, parallel computing, and integration with experimental data.

### 🔑 Key Keywords
`Computational Neuroscience` • `Brain Simulation` • `Neural Modeling` • `Multi-scale Simulation` • `Spiking Neural Networks` • `Neuroinformatics` • `Biophysical Modeling` • `Stochastic Simulation` • `Reaction-Diffusion` • `Open Source Neuroscience`

---

## 🗺️ Table of Contents
- [🚀 SaaS / Hosted Platforms](#saas--hosted-platforms)
- [💻 Open-Source GitHub Projects](#open-source-github-projects)
- [🤝 How to Contribute](#how-to-contribute)
- [⚖️ Disclaimer](#disclaimer)
- [📈 Star History](#star-history)

---

## 🚀 SaaS / Hosted Platforms

| Platform | Primary Use Case | Pricing & Free Tier |
| :--- | :--- | :--- |
| **[Open Source Brain (OSBv2)](https://v2.opensourcebrain.org/)** | Collaborative modeling, visualization, and cloud-based simulation (NetPyNE, Jupyter). | **Free** (Academic). Provides persistent cloud workspaces and integrated simulation tools. |
| **[Neuroscience Gateway (NSG)](https://www.nsgportal.org/)** | Running large-scale parallel simulations (NEURON, Brian2, NEST) on supercomputers. | **Free** (Academic). Initial allocation of **20,000 core hours/year**; supplemental requests possible. |
| **[EBRAINS](https://ebrains.eu/)** | European research infrastructure for brain research, simulation, and data analysis. | **Free** for researchers and students. Includes JupyterLab and HPC access. |
| **[The Virtual Brain (TVB) Cloud](https://thevirtualbrain.org/)** | Personalized brain network modeling and clinical simulation. | **Free** (Open-source and hosted via EBRAINS infrastructure). |
| **[NetPyNE-UI (Hosted)](http://netpyne.opensourcebrain.org/)** | Web-based GUI for building and simulating large-scale biological networks. | **Free** (Hosted via OSB/NSG). No subscription fees. |
| **[ModelDB](https://modeldb.yale.edu/)** | Repository of models with "Run in ModelDB" integration for quick cloud testing. | **Free**. Integrated with OSB for one-click simulation execution. |
| **Self-Hosted (AWS/GCP/Azure)** | Private, custom-scaled instances of any open-source simulator. | **Pay-as-you-go** based on cloud provider infrastructure costs (vCPU/GPU/Storage). |

---

<div align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNHJndzZ4N3F5Znd6Z3Z4Z3Z4Z3Z4Z3Z4Z3Z4Z3Z4Z3Z4Z3Z4JmVwPXYxX2ludGVybmFsX2dpZl9ieV9pZCZjdD1n/3o7TKVUn7iM8FMEU24/giphy.gif" width="600" alt="Neural Simulation Animation">
  <p><i>Visualizing neural activity and network dynamics.</i></p>
</div>

---

## 💻 Open-Source GitHub Projects

### Dedicated Multi-Scale Neuronal Simulation Projects 🛠️

- **[NEURON Simulator](https://github.com/neuronsimulator/nrn)** 🖥️  
  The leading open-source simulator for biologically detailed neuron and network models. Supports Hodgkin-Huxley style compartmental modeling, reaction-diffusion, and Python scripting.

- **[CoreNEURON](https://github.com/neuronsimulator/nrn/tree/master/src/coreneuron)** 🏎️  
  (Integrated in NEURON) High-performance compute engine optimized for large-scale parallel simulations of detailed neuronal networks.

- **[MOOSE (BhallaLab)](https://github.com/BhallaLab/moose)** 🧬  
  Multiscale Object-Oriented Simulation Environment for modeling from biochemical signaling pathways to full neuronal networks and circuits.

- **[STEPS](https://github.com/CNS-OIST/STEPS)** 🧪  
  STochastic Engine for Pathway Simulation — supports exact stochastic simulation of reaction-diffusion systems in complex 3D cellular geometries.

- **[Arbor](https://github.com/arbor-sim/arbor)** 🚀  
  Modern, performance-portable library for multi-compartment neuron network simulations. Designed for scalability on CPUs and accelerators.

- **[NetPyNE](https://github.com/suny-downstate-medical-center/netpyne)** 📊  
  High-level Python interface for NEURON. Simplifies development, parallel simulation, optimization, and analysis of large-scale neuronal networks.

- **[Open Source Brain (OSB)](https://github.com/OpenSourceBrain)** 🌍  
  Platform and tools for sharing, simulating, and collaborating on neuronal models, with strong support for NeuroML standards.

- **[ModelDB](https://modeldb.yale.edu/)** 📚  
  Curated repository of published computational neuroscience models, many compatible with NEURON, MOOSE, and other simulators.

### Additional Strong Open-Source Options 🔗

- **[Brian 2](https://github.com/brian-team/brian2)** — Flexible Python simulator for spiking neural networks with emphasis on ease of use. 🐍
- **[NEST Simulator](https://github.com/nest/nest-simulator)** — Leading simulator for large-scale spiking neural networks. 🏗️
- **[NeuroML](https://github.com/NeuroML)** — Standard for describing and exchanging multi-scale neuronal models. 📝
- **PhysiCell** — For hybrid neuro-biological modeling and extensions. 🧫

---

## 🤝 How to Contribute

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## ⚖️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Simulation accuracy depends on model parameters, validation against experimental data, and appropriate numerical methods.
- For research publications, cite the original tool papers and ensure compliance with licenses.

---

<div align="center">
  <b>Made with ❤️ for computational neuroscientists, systems biologists, and researchers.</b>
</div>

## 📈 Star History

<div align="center">
  <a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-Neuron&type=date&legend=bottom-right">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Neuron&type=date&theme=dark&legend=bottom-right" />
      <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Neuron&type=date&legend=bottom-right" />
      <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Neuron&type=date&legend=bottom-right" />
    </picture>
  </a>
</div>

