# Awesome Generative AI for Material Discovery

<p align="center">
  <a href="https://github.com/yanliang3612/Awesome-Generative-AI-for-Material-Discovery">
    <img src="https://awesome.re/badge.svg" alt="Awesome">
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License: MIT">
  </a>
</p>

<p align="center">
  <img src="assets/generative-ai-materials-logo.png" alt="Generative AI for Material Discovery logo" width="260">
</p>

<p align="center">
  <strong>A curated collection of papers, projects, datasets, and benchmarks on generative AI for material discovery.</strong>
</p>

<p align="center">
  <a href="https://github.com/yanliang3612/Awesome-Generative-AI-for-Material-Discovery">Project Page</a>
  |
  <a href="#awesome-papers">Papers</a>
  |
  <a href="#awesome-datasets-benchmarks--toolkits">Datasets & Toolkits</a>
  |
  <a href="#citation">Citation</a>
</p>

Last updated: 2026-07-10

---

## Table of Contents

- [Overview](#overview)
- [Awesome Papers](#awesome-papers)
  - [Surveys & Benchmarks](#surveys--benchmarks)
  - [Large Language Models](#large-language-models)
  - [Agentic Materials Discovery](#agentic-materials-discovery)
  - [Diffusion Models](#diffusion-models)
  - [Flow Matching Models](#flow-matching-models)
  - [Symmetry-Aware & Wyckoff Generation](#symmetry-aware--wyckoff-generation)
  - [VAE Models](#vae-models)
  - [MOF & Porous Materials](#mof--porous-materials)
  - [Representation & Pretraining](#representation--pretraining)
  - [Multi-Modal Training & Learning](#multi-modal-training--learning)
- [Awesome Datasets, Benchmarks & Toolkits](#awesome-datasets-benchmarks--toolkits)
- [Citation](#citation)
- [Contact](#contact)

---

## Overview

This repository tracks recent progress in generative AI for materials, including language-model-based crystal generation, diffusion and flow-matching models, VAE-style generators, multimodal materials learning, agentic discovery workflows, foundation models, and evaluation resources.

**Legend:** `Code` links to implementations or official repositories when available; `Demo` links to project pages, leaderboards, web apps, or documentation.

## Awesome Papers

### Surveys & Benchmarks

| Title | Venue | Date | Code | Demo |
| - | - | - | - | - |
| [**Pretraining Strategies for Structure Agnostic Material Property Prediction**](https://pubs.acs.org/doi/10.1021/acs.jcim.3c00919) | Journal of Chemical Information and Modeling 2024 | 2024.02.01 | - | - |
| [**Artificial Intelligence Driving Materials Discovery? Perspective on the Article: Scaling Deep Learning for Materials Discovery**](https://pubs.acs.org/doi/10.1021/acs.chemmater.4c00643) | Chemistry of Materials 2024 | 2024.08.08 | - | - |
| [**Matbench Discovery -- A framework to evaluate machine learning crystal stability predictions**](https://arxiv.org/abs/2308.14920) | arXiv 2023 | 2023.08.28 | [GitHub](https://github.com/janosh/matbench-discovery) | [Leaderboard](https://matbench-discovery.materialsproject.org/) |
| [**LeMat-GenBench: A Unified Evaluation Framework for Crystal Generative Models**](https://arxiv.org/abs/2512.04562) | arXiv 2025 | 2025.12.04 | - | - |
| [**Are Machine Learning Interatomic Potentials Truly Practical? A Benchmark of 23 Mainstream Models**](https://arxiv.org/abs/2607.07647) | arXiv 2026 | 2026.07.08 | - | - |

### Large Language Models

| Title | Venue | Date | Code | Demo |
| - | - | - | - | - |
| [**ChatGPT in the Material Design: Selected Case Studies to Assess the Potential of ChatGPT**](https://pubs.acs.org/doi/10.1021/acs.jcim.3c01702) | Journal of Chemical Information and Modeling 2024 | 2024.01.18 | - | - |
| ![Star](https://img.shields.io/github/stars/facebookresearch/crystal-text-llm.svg?style=social&label=Star)<br>[**Fine-Tuned Language Models Generate Stable Inorganic Materials as Text**](https://arxiv.org/abs/2402.04379) | ICLR 2024 | 2024.02.06 | [GitHub](https://github.com/facebookresearch/crystal-text-llm) | - |
| ![Star](https://img.shields.io/github/stars/lantunes/CrystaLLM.svg?style=social&label=Star)<br>[**Crystal structure generation with autoregressive large language modeling**](https://www.nature.com/articles/s41467-024-54639-7) | Nature Communications 2024 | 2024.11.28 | [GitHub](https://github.com/lantunes/CrystaLLM) | - |
| ![Star](https://img.shields.io/github/stars/usnistgov/atomgpt.svg?style=social&label=Star)<br>[**AtomGPT: Atomistic Generative Pre-trained Transformer for Forward and Inverse Materials Design**](https://arxiv.org/abs/2405.03680) | arXiv 2024 | 2024.05.06 | [GitHub](https://github.com/usnistgov/atomgpt) | - |
| ![Star](https://img.shields.io/github/stars/harrylaucngd/prompt-eng-master.svg?style=social&label=Star)<br>[**Integrating Chemistry Knowledge in Large Language Models via Prompt Engineering**](https://arxiv.org/abs/2404.14467) | arXiv 2024 | 2024.05.22 | [GitHub](https://github.com/harrylaucngd/prompt-eng-master) | - |
| ![Star](https://img.shields.io/github/stars/Fung-Lab/LLMatDesign.svg?style=social&label=Star)<br>[**LLMatDesign: Autonomous Materials Discovery with Large Language Models**](https://arxiv.org/abs/2406.13163) | arXiv 2024 | 2024.06.19 | [GitHub](https://github.com/Fung-Lab/LLMatDesign) | - |
| ![Star](https://img.shields.io/github/stars/xiaohang007/SLICES.svg?style=social&label=Star)<br>[**MatterGPT: A Generative Transformer for Multi-Property Inverse Design of Solid-State Materials**](https://arxiv.org/abs/2408.07608) | arXiv 2024 | 2024.08.14 | [GitHub](https://github.com/xiaohang007/SLICES/tree/main/MatterGPT) | - |
| ![Star](https://img.shields.io/github/stars/divelab/AIRS.svg?style=social&label=Star)<br>[**Invariant Tokenization of Crystalline Materials for Language Model Enabled Generation**](https://arxiv.org/abs/2503.00152) | arXiv 2025 | 2025.02.28 | [GitHub](https://github.com/divelab/AIRS/tree/main/OpenMat/Mat2Seq) | - |
| [**MatLLMSearch: Crystal Structure Discovery with Evolution-Guided Large Language Models**](https://arxiv.org/abs/2502.20933) | arXiv 2025 | 2025.02.28 | - | - |
| [**A generative material transformer using Wyckoff representation**](https://arxiv.org/abs/2501.16051) | arXiv 2025 | 2025.01.27 | - | - |
| [**CrystalICL: Enabling In-Context Learning for Crystal Generation**](https://arxiv.org/abs/2508.20143) | arXiv 2025 | 2025.08.27 | - | - |

### Agentic Materials Discovery

| Title | Venue | Date | Code | Demo |
| - | - | - | - | - |
| ![Star](https://img.shields.io/github/stars/Fung-Lab/LLMatDesign.svg?style=social&label=Star)<br>[**LLMatDesign: Autonomous Materials Discovery with Large Language Models**](https://arxiv.org/abs/2406.13163) | arXiv 2024 | 2024.06.19 | [GitHub](https://github.com/Fung-Lab/LLMatDesign) | - |
| [**GenMS: Generative Hierarchical Materials Search**](https://arxiv.org/abs/2409.06762) | NeurIPS 2024 | 2024.09.10 | - | [Demo](https://generative-materials.github.io/genms/) |
| ![Star](https://img.shields.io/github/stars/adibgpt/Multicrossmodal-Autonomous-Materials-Science-Agent.svg?style=social&label=Star)<br>[**Multicrossmodal Automated Agent for Integrating Diverse Materials Science Data**](https://arxiv.org/abs/2505.15132) | arXiv 2025 | 2025.05.21 | [GitHub](https://github.com/adibgpt/Multicrossmodal-Autonomous-Materials-Science-Agent) | - |
| [**"DIVE" into Hydrogen Storage Materials Discovery with AI Agents**](https://arxiv.org/abs/2508.13251) | arXiv 2025 | 2025.08.18 | - | - |
| [**PolyJarvis: An LLM-Orchestrated Agent for Automated All-Atom Molecular Dynamics of Amorphous Homopolymers**](https://arxiv.org/abs/2604.02537) | arXiv 2026 | 2026.04.02 | - | - |

### Diffusion Models

| Title | Venue | Date | Code | Demo |
| - | - | - | - | - |
| ![Star](https://img.shields.io/github/stars/jiaor17/DiffCSP.svg?style=social&label=Star)<br>[**Crystal Structure Prediction by Joint Equivariant Diffusion**](https://arxiv.org/abs/2309.04475) | NeurIPS 2023 | 2023.07.30 | [GitHub](https://github.com/jiaor17/DiffCSP) | - |
| ![Star](https://img.shields.io/github/stars/microsoft/MOFDiff.svg?style=social&label=Star)<br>[**MOFDiff: Coarse-grained Diffusion for Metal-Organic Framework Design**](https://arxiv.org/abs/2310.10732) | ICLR 2024 | 2023.10.16 | [GitHub](https://github.com/microsoft/MOFDiff) | - |
| [**UniMat: Scalable Diffusion for Materials Generation**](https://arxiv.org/abs/2311.09235) | arXiv 2023 | 2023.11.15 | - | [Demo](https://unified-materials.github.io/unimat/) |
| ![Star](https://img.shields.io/github/stars/microsoft/mattergen.svg?style=social&label=Star)<br>[**MatterGen: A Generative Model for Inorganic Materials Design**](https://arxiv.org/abs/2312.03687) | Nature 2025 | 2023.12.06 | [GitHub](https://github.com/microsoft/mattergen) | - |
| ![Star](https://img.shields.io/github/stars/jiaor17/DiffCSP-PP.svg?style=social&label=Star)<br>[**Space Group Constrained Crystal Generation**](https://arxiv.org/abs/2402.03992) | ICLR 2024 | 2024.02.06 | [GitHub](https://github.com/jiaor17/DiffCSP-PP) | - |
| ![Star](https://img.shields.io/github/stars/EmperorJia/EquiCSP.svg?style=social&label=Star)<br>[**Equivariant Diffusion for Crystal Structure Prediction**](https://dl.acm.org/doi/10.5555/3692070.3693274) | ICML 2024 | 2024.07.21 | [GitHub](https://github.com/EmperorJia/EquiCSP) | - |
| [**Discovery of 2D Materials via Symmetry-Constrained Diffusion Model**](https://doi.org/10.1021/acs.jpcc.4c08681) | J. Phys. Chem. C 2025 | 2024.12.24 | - | - |
| [**Generative Design of Crystal Structures by Point Cloud Representations and Diffusion Model**](https://doi.org/10.1016/j.isci.2024.111659) | iScience 2025 | 2025.01.17 | - | - |
| [**Atomistic Generative Diffusion for Materials Modeling**](https://arxiv.org/abs/2501.08117) | arXiv 2025 | 2025.01.14 | - | - |
| [**DiffCrysGen: A Score-Based Diffusion Model for Design of Diverse Inorganic Crystalline Materials**](https://arxiv.org/abs/2505.07442) | arXiv 2025 | 2025.05.12 | - | - |
| ![Star](https://img.shields.io/github/stars/facebookresearch/all-atom-diffusion-transformer.svg?style=social&label=Star)<br>[**All-atom Diffusion Transformers: Unified generative modelling of molecules and materials**](https://arxiv.org/abs/2503.03965) | arXiv 2025 | 2025.03.05 | [GitHub](https://github.com/facebookresearch/all-atom-diffusion-transformer) | - |
| ![Star](https://img.shields.io/github/stars/hanyi2021/CrystalDiT.svg?style=social&label=Star)<br>[**CrystalDiT: A Diffusion Transformer for Crystal Generation**](https://arxiv.org/abs/2508.16614) | arXiv 2025 | 2025.08.13 | [GitHub](https://github.com/hanyi2021/CrystalDiT) | - |
| ![Star](https://img.shields.io/github/stars/joshrosie/crystalite.svg?style=social&label=Star)<br>[**Crystalite: A Lightweight Transformer for Efficient Crystal Modeling**](https://arxiv.org/abs/2604.02270) | arXiv 2026 | 2026.04.02 | [GitHub](https://github.com/joshrosie/crystalite) | - |

### Flow Matching Models

| Title | Venue | Date | Code | Demo |
| - | - | - | - | - |
| ![Star](https://img.shields.io/github/stars/chao1224/CrystalFlow.svg?style=social&label=Star)<br>[**An Equivariant Flow Matching Framework for Learning Molecular Crystallization**](https://openreview.net/forum?id=lCVqpQvr4l) | ICML 2024 Workshop | 2024.06.17 | [GitHub](https://github.com/chao1224/CrystalFlow) | - |
| ![Star](https://img.shields.io/github/stars/facebookresearch/flowmm.svg?style=social&label=Star)<br>[**FlowMM: Generating Materials with Riemannian Flow Matching**](https://arxiv.org/abs/2406.04713) | ICML 2024 | 2024.07.07 | [GitHub](https://github.com/facebookresearch/flowmm) | - |
| ![Star](https://img.shields.io/github/stars/facebookresearch/flowmm.svg?style=social&label=Star)<br>[**FlowLLM: Flow Matching for Material Generation with Large Language Models as Base Distributions**](https://arxiv.org/abs/2410.23405) | NeurIPS 2024 | 2024.10.30 | [GitHub](https://github.com/facebookresearch/flowmm) | - |
| [**Space Group Conditional Flow Matching**](https://arxiv.org/abs/2509.23822) | arXiv 2025 | 2025.09.28 | - | - |
| [**Flexible MOF Generation with Torsion-Aware Flow Matching**](https://arxiv.org/abs/2505.17914) | arXiv 2025 | 2025.05.23 | - | - |
| [**DMFlow: Disordered Materials Generation by Flow Matching**](https://arxiv.org/abs/2602.04734) | arXiv 2026 | 2026.02.04 | - | - |
| [**Generating Symmetric Materials using Latent Flow Matching**](https://arxiv.org/abs/2605.10115) | arXiv 2026 | 2026.05.11 | - | - |

### Symmetry-Aware & Wyckoff Generation

| Title | Venue | Date | Code | Demo |
| - | - | - | - | - |
| ![Star](https://img.shields.io/github/stars/jiaor17/DiffCSP-PP.svg?style=social&label=Star)<br>[**Space Group Constrained Crystal Generation**](https://arxiv.org/abs/2402.03992) | ICLR 2024 | 2024.02.06 | [GitHub](https://github.com/jiaor17/DiffCSP-PP) | - |
| [**SymmCD: Symmetry-Preserving Crystal Generation with Diffusion Models**](https://arxiv.org/abs/2502.03638) | arXiv 2025 | 2025.02.05 | - | - |
| [**WyckoffDiff -- A Generative Diffusion Model for Crystal Symmetry**](https://arxiv.org/abs/2502.06485) | arXiv 2025 | 2025.02.10 | - | - |
| [**A generative material transformer using Wyckoff representation**](https://arxiv.org/abs/2501.16051) | arXiv 2025 | 2025.01.27 | - | - |
| [**Space Group Conditional Flow Matching**](https://arxiv.org/abs/2509.23822) | arXiv 2025 | 2025.09.28 | - | - |
| [**Symmetry-aware Conditional Generation of Crystal Structures Using Diffusion Models**](https://arxiv.org/abs/2601.08115) | arXiv 2026 | 2026.01.13 | - | - |
| [**Generating Symmetric Materials using Latent Flow Matching**](https://arxiv.org/abs/2605.10115) | arXiv 2026 | 2026.05.11 | - | - |

### VAE Models

| Title | Venue | Date | Code | Demo |
| - | - | - | - | - |
| ![Star](https://img.shields.io/github/stars/txie-93/cdvae.svg?style=social&label=Star)<br>[**Crystal Diffusion Variational Autoencoder for Periodic Material Generation**](https://arxiv.org/abs/2110.06197) | ICLR 2022 | 2021.10.21 | [GitHub](https://github.com/txie-93/cdvae) | - |
| ![Star](https://img.shields.io/github/stars/ixsluo/cond-cdvae.svg?style=social&label=Star)<br>[**Deep learning generative model for crystal structure prediction**](https://www.nature.com/articles/s41524-024-01443-y) | npj Computational Materials 2024 | 2024.08.10 | [GitHub](https://github.com/ixsluo/cond-cdvae) | - |
| [**VQCrystal: Leveraging Vector Quantization for Discovery of Stable Crystal Structures**](https://arxiv.org/abs/2409.06191) | arXiv 2024 | 2024.09.10 | - | - |
| ![Star](https://img.shields.io/github/stars/MaterSim/LEGO-xtal.svg?style=social&label=Star)<br>[**AI-Assisted Rapid Crystal Structure Generation Towards a Target Local Environment**](https://arxiv.org/abs/2506.08224) | arXiv 2025 | 2025.06.09 | [GitHub](https://github.com/MaterSim/LEGO-xtal) | [Demo](http://lego-crystal.onrender.com) |

### MOF & Porous Materials

| Title | Venue | Date | Code | Demo |
| - | - | - | - | - |
| ![Star](https://img.shields.io/github/stars/microsoft/MOFDiff.svg?style=social&label=Star)<br>[**MOFDiff: Coarse-grained Diffusion for Metal-Organic Framework Design**](https://arxiv.org/abs/2310.10732) | ICLR 2024 | 2023.10.16 | [GitHub](https://github.com/microsoft/MOFDiff) | - |
| ![Star](https://img.shields.io/github/stars/parkjunkil/MOFFUSION.svg?style=social&label=Star)<br>[**Multi-modal Conditioning for Metal-Organic Frameworks Generation Using 3D Modeling Techniques**](https://www.nature.com/articles/s41467-024-55390-9) | Nature Communications 2025 | 2024.07.05 | [GitHub](https://github.com/parkjunkil/MOFFUSION) | [Demo](https://parkjunkil.github.io/MOFFUSION/) |
| [**MOFA: Discovering Materials for Carbon Capture with a GenAI- and Simulation-Based Workflow**](https://arxiv.org/abs/2501.10651) | arXiv 2025 | 2025.01.18 | - | - |
| [**Flexible MOF Generation with Torsion-Aware Flow Matching**](https://arxiv.org/abs/2505.17914) | arXiv 2025 | 2025.05.23 | - | - |
| ![Star](https://img.shields.io/github/stars/nayoung10/AtomMOF.svg?style=social&label=Star)<br>[**AtomMOF: All-Atom Flow Matching for MOF-Adsorbate Structure Prediction**](https://arxiv.org/abs/2602.07351) | arXiv 2026 | 2026.02.07 | [GitHub](https://github.com/nayoung10/AtomMOF) | - |
| [**L^2M^3OF: A Large Language Multimodal Model for Metal-Organic Frameworks**](https://arxiv.org/abs/2510.20976) | arXiv 2025 | 2025.10.23 | - | - |

### Representation & Pretraining

| Title | Venue | Date | Code | Demo |
| - | - | - | - | - |
| ![Star](https://img.shields.io/github/stars/YKQ98/Matformer.svg?style=social&label=Star)<br>[**Periodic Graph Transformers for Crystal Material Property Prediction**](https://arxiv.org/abs/2209.11807) | NeurIPS 2022 | 2022.09.23 | [GitHub](https://github.com/YKQ98/Matformer) | - |
| [**Resolving the data ambiguity for periodic crystals**](https://openreview.net/forum?id=4wrB7Mo9_OQ) | NeurIPS 2022 | 2022.11.28 | - | - |
| [**Capturing long-range interaction with reciprocal space neural network**](https://arxiv.org/abs/2211.16684) | arXiv 2022 | 2022.11.30 | - | - |
| [**A Crystal-Specific Pre-Training Framework for Crystal Material Property Prediction**](https://arxiv.org/abs/2306.05344) | arXiv 2023 | 2023.06.08 | - | - |
| ![Star](https://img.shields.io/github/stars/divelab/AIRS.svg?style=social&label=Star)<br>[**Efficient Approximations of Complete Interatomic Potentials for Crystal Property Prediction**](https://arxiv.org/abs/2306.10045) | ICML 2023 | 2023.06.12 | [GitHub](https://github.com/divelab/AIRS/tree/main/OpenMat/PotNet) | - |
| ![Star](https://img.shields.io/github/stars/facebookresearch/JMP.svg?style=social&label=Star)<br>[**From Molecules to Materials: Pre-training Large Generalizable Models for Atomic Property Prediction**](https://arxiv.org/abs/2310.16802) | ICLR 2024 | 2023.10.25 | [GitHub](https://github.com/facebookresearch/JMP) | - |
| ![Star](https://img.shields.io/github/stars/divelab/AIRS.svg?style=social&label=Star)<br>[**Complete and Efficient Graph Transformers for Crystal Material Property Prediction**](https://arxiv.org/abs/2403.11857) | ICLR 2024 | 2024.03.18 | [GitHub](https://github.com/divelab/AIRS) | - |
| [**A Diffusion-Based Pre-training Framework for Crystal Property Prediction**](https://ojs.aaai.org/index.php/AAAI/article/view/28748) | AAAI 2024 | 2024.03.24 | - | - |
| ![Star](https://img.shields.io/github/stars/microsoft/mattersim.svg?style=social&label=Star)<br>[**MatterSim: A Deep Learning Atomistic Model Across Elements, Temperatures and Pressures**](https://arxiv.org/abs/2405.04967) | arXiv 2024 | 2024.05.08 | [GitHub](https://github.com/microsoft/mattersim) | [Docs](https://microsoft.github.io/mattersim/) |
| ![Star](https://img.shields.io/github/stars/materialsvirtuallab/matgl.svg?style=social&label=Star)<br>[**Materials Graph Library**](https://github.com/materialsvirtuallab/matgl) | Project 2026 | 2026.05.05 | [GitHub](https://github.com/materialsvirtuallab/matgl) | [Docs](https://matgl.ai) |
| [**MatRIS: Toward Reliable and Efficient Pretrained Machine Learning Interaction Potentials**](https://arxiv.org/abs/2603.02002) | arXiv 2026 | 2026.03.02 | - | - |
| [**DPA4: Pushing the Accuracy-Cost Frontier of Interatomic Potentials with EMFA SO(2) Convolution**](https://arxiv.org/abs/2606.02419) | arXiv 2026 | 2026.06.01 | - | - |

### Multi-Modal Training & Learning

| Title | Venue | Date | Code | Demo |
| - | - | - | - | - |
| ![Star](https://img.shields.io/github/stars/vertaix/LLM-Prop.svg?style=social&label=Star)<br>[**LLM-Prop: Predicting Physical And Electronic Properties of Crystalline Solids From Their Text Descriptions**](https://arxiv.org/abs/2310.14029) | arXiv 2023 | 2023.10.21 | [GitHub](https://github.com/vertaix/LLM-Prop) | - |
| [**Multimodal learning for crystalline materials**](https://arxiv.org/abs/2312.00111) | arXiv 2023 | 2023.11.30 | - | - |
| [**LBNL: A foundation model for atomistic materials chemistry**](https://arxiv.org/abs/2401.00096) | arXiv 2023 | 2023.12.29 | - | - |
| [**Materials science in the era of large language models: a perspective**](https://arxiv.org/abs/2403.06949) | Digital Discovery 2024 | 2024.03.11 | - | - |
| ![Star](https://img.shields.io/github/stars/kdmsit/crysmmnet.svg?style=social&label=Star)<br>[**CrysMMNet: Multimodal Representation for Crystal Property Prediction**](https://arxiv.org/abs/2307.05390) | UAI 2023 | 2024.06.09 | [GitHub](https://github.com/kdmsit/crysmmnet) | - |
| ![Star](https://img.shields.io/github/stars/lamalab-org/MatText.svg?style=social&label=Star)<br>[**MatText: Do Language Models Need More than Text & Scale for Materials Modeling?**](https://arxiv.org/abs/2406.17295) | arXiv 2024 | 2024.06.25 | [GitHub](https://github.com/lamalab-org/MatText) | - |
| ![Star](https://img.shields.io/github/stars/parkjunkil/MOFFUSION.svg?style=social&label=Star)<br>[**Multi-modal conditioning for metal-organic frameworks generation using 3D modeling techniques**](https://www.nature.com/articles/s41467-024-55390-9) | Nature Communications 2025 | 2024.07.05 | [GitHub](https://github.com/parkjunkil/MOFFUSION) | [Demo](https://parkjunkil.github.io/MOFFUSION/) |
| ![Star](https://img.shields.io/github/stars/lamalab-org/matextract-book.svg?style=social&label=Star)<br>[**From Text to Insight: Large Language Models for Materials Science Data Extraction**](https://arxiv.org/abs/2407.16867) | arXiv 2024 | 2024.07.23 | [GitHub](https://github.com/lamalab-org/matextract-book) | - |
| [**Graph-Text Contrastive Learning of Inorganic Crystal Structure toward a Foundation Model of Inorganic Materials**](https://chemrxiv.org/engage/chemrxiv/article-details/661bd38821291e5d1dd0f10b) | ChemRxiv 2024 | 2024.08.15 | - | - |
| ![Star](https://img.shields.io/github/stars/adibgpt/Multicrossmodal-Autonomous-Materials-Science-Agent.svg?style=social&label=Star)<br>[**Multicrossmodal Automated Agent for Integrating Diverse Materials Science Data**](https://arxiv.org/abs/2505.15132) | arXiv 2025 | 2025.05.21 | [GitHub](https://github.com/adibgpt/Multicrossmodal-Autonomous-Materials-Science-Agent) | - |
| [**"DIVE" into Hydrogen Storage Materials Discovery with AI Agents**](https://arxiv.org/abs/2508.13251) | arXiv 2025 | 2025.08.18 | - | - |
| [**L^2M^3OF: A Large Language Multimodal Model for Metal-Organic Frameworks**](https://arxiv.org/abs/2510.20976) | arXiv 2025 | 2025.10.23 | - | - |
| [**Unlocking the Visual Record of Materials Science: A Large-Scale Multimodal Dataset from Scientific Literature**](https://arxiv.org/abs/2606.29667) | arXiv 2026 | 2026.06.29 | - | - |

## Awesome Datasets, Benchmarks & Toolkits

| Name | Type | Year | Code / Resource | Notes |
| - | - | - | - | - |
| [**MatterGen**](https://github.com/microsoft/mattergen) | Generative model | 2025 | [GitHub](https://github.com/microsoft/mattergen) | Inorganic material generation from Microsoft Research. |
| [**ADiT**](https://github.com/facebookresearch/all-atom-diffusion-transformer) | Generative model | 2025 | [GitHub](https://github.com/facebookresearch/all-atom-diffusion-transformer) | Unified all-atom diffusion transformer for molecules and materials. |
| [**CrystalDiT**](https://github.com/hanyi2021/CrystalDiT) | Generative model | 2025 | [GitHub](https://github.com/hanyi2021/CrystalDiT) | Simple diffusion transformer for crystal generation. |
| [**Crystalite**](https://github.com/joshrosie/crystalite) | Generative model | 2026 | [GitHub](https://github.com/joshrosie/crystalite) | Lightweight diffusion transformer for crystalline materials. |
| [**FlowMM**](https://github.com/facebookresearch/flowmm) | Generative model | 2024 | [GitHub](https://github.com/facebookresearch/flowmm) | Riemannian flow matching for materials. |
| [**Crystal-text-LLM**](https://github.com/facebookresearch/crystal-text-llm) | Language model | 2024 | [GitHub](https://github.com/facebookresearch/crystal-text-llm) | CIF/text-based stable inorganic material generation. |
| [**MatterGPT**](https://github.com/xiaohang007/SLICES/tree/main/MatterGPT) | Language model | 2024 | [GitHub](https://github.com/xiaohang007/SLICES/tree/main/MatterGPT) | SLICES-based transformer for multi-property inverse design. |
| [**MOFFUSION**](https://github.com/parkjunkil/MOFFUSION) | MOF generator | 2025 | [GitHub](https://github.com/parkjunkil/MOFFUSION) | Multi-modal MOF generation with 3D conditioning. |
| [**AtomMOF**](https://github.com/nayoung10/AtomMOF) | MOF generator | 2026 | [GitHub](https://github.com/nayoung10/AtomMOF) | All-atom flow matching for MOF-adsorbate structure prediction. |
| [**MatterSim**](https://github.com/microsoft/mattersim) | Atomistic foundation model | 2024 | [GitHub](https://github.com/microsoft/mattersim) | General atomistic model across elements, temperatures, and pressures. |
| [**MatGL**](https://github.com/materialsvirtuallab/matgl) | Materials graph library | 2026 | [GitHub](https://github.com/materialsvirtuallab/matgl) | Graph deep learning library with pretrained materials models. |
| [**Open Materials 2024 (OMat24)**](https://arxiv.org/abs/2410.12771) | Dataset & pretrained models | 2024 | [Fairchem](https://github.com/facebookresearch/fairchem) | Large-scale inorganic materials dataset and pretrained models. |
| [**Matbench Discovery**](https://matbench-discovery.materialsproject.org/) | Benchmark | 2023 | [GitHub](https://github.com/janosh/matbench-discovery) | Stability prediction benchmark and leaderboard. |
| [**LeMat-GenBench**](https://arxiv.org/abs/2512.04562) | Generative benchmark | 2025 | - | Unified evaluation framework for crystal generative models. |
| [**MatMMExtract / MatSciFig / MaterialScope**](https://arxiv.org/abs/2606.29667) | Multimodal dataset | 2026 | - | Pipeline and datasets for figure-level materials vision-language learning. |
| [**Multicrossmodal Autonomous Materials Science Agent**](https://github.com/adibgpt/Multicrossmodal-Autonomous-Materials-Science-Agent) | Agent framework | 2025 | [GitHub](https://github.com/adibgpt/Multicrossmodal-Autonomous-Materials-Science-Agent) | Multi-agent integration of materials images, videos, tables, and literature. |

## Citation

If you find this repository useful for your research, please consider citing it:

```bibtex
@misc{yan2026awesomegenerativeaimaterialdiscovery,
  title        = {Awesome Generative AI for Material Discovery},
  author       = {Yan, Liang},
  year         = {2026},
  howpublished = {\url{https://github.com/yanliang3612/Awesome-Generative-AI-for-Material-Discovery}},
  note         = {GitHub repository}
}
```

## Contact

For any questions, feedback, or collaboration regarding this repository of papers and code, feel free to contact Liang Yan at [yanliangfdu@gmail.com]().
