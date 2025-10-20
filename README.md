# Alloy_Design
### A Unified AI–Quantum–Physics Framework for Autonomous Alloy Discovery and Multi-Property Materials Design  

**Principal Investigator:**  
**Akash Kanji**  
Department of Metallurgical and Materials Engineering, Jadavpur University  
Visiting Researcher, Washington State University  

---

## Vision

The **Alloy_Design** project — codenamed **Project TitanForge** — aims to revolutionize alloy discovery by integrating **Artificial Intelligence, Physics-Informed Modeling, and Quantum Computation** into a single autonomous platform.

Our mission is to build a **Universal Materials Intelligence System** capable of learning from atomic structures, generating novel compositions, and predicting mechanical, thermal, electronic, and chemical properties — all while remaining physically interpretable and experimentally grounded.

We envision TitanForge as the next-generation digital forge for materials — where atoms, physics, and computation converge to accelerate innovation in steels, superalloys, and energy materials.

---

## Core Research Streams

The repository is organized into **four major research streams (A–D)**. Each stream contains specific modules (A1–D4) with code, datasets, and models.

---

### Stream A – Foundation Models

_"Teaching AI the language of atoms."_

Focus: Large-scale representation learning and predictive modeling of materials properties.

#### Modules
- **A1_ElementEmbeddings/** – Elemental and atomic vector representations using physics-informed descriptors and self-supervised learning.  
- **A2_GNN_MultiProperty/** – Multi-task Graph Neural Network (GNN) model predicting multiple materials properties (E, σ, κ, Eg).  
- **A3_TransformerGNN/** – Transformer-GNN hybrid capturing long-range interactions and crystal symmetry.  
- **A4_MatFold_Benchmark/** – Open benchmark for materials ML with standardized splits and cross-validation protocols.

Goal: Develop a **foundation-scale model** (MatFM) trained on 1M+ crystal structures to predict mechanical and electronic properties simultaneously.

---

### Stream B – Generative and Inverse Design

_"Designing materials backwards — from desired properties to atomic structure."_

Focus: Generative AI for alloy and microstructure design using Diffusion, GANs, and inverse modeling.

#### Modules
- **B1_DiffusionCrystalGen/** – Diffusion-based model for property-conditioned crystal structure generation.  
- **B2_InverseDesign/** – Neural inverse mapping: target property → optimal composition/structure.  
- **B3_StabilityAwareGen/** – Phase diagram–guided generator ensuring thermodynamic feasibility.  
- **B4_PolymerOrganicGen/** – Extending inverse design to polymeric and organic material systems.

Goal: Build a **conditional generative engine** that autonomously proposes stable, high-performance alloys and composites.

---

### Stream C – Physics-Integrated and Quantum ML

_"Embedding the laws of physics and the power of quantum computation into learning."_

Focus: Combining numerical physics, differential modeling, and quantum-enhanced algorithms.

#### Modules
- **C1_PINN_PhaseField/** – Physics-Informed Neural Network for diffusion, segregation, and phase-field simulations.  
- **C2_DFT_Surrogate/** – Multi-fidelity surrogate model for Density Functional Theory (DFT) with uncertainty quantification (UQ).  
- **C3_QML_Superposition/** – Quantum ML module using variational quantum eigensolvers (VQE) for low-energy state search and superposition sampling.  
- **C4_MultiFidelity/** – Hierarchical surrogate learning linking empirical → DFT → experimental fidelity levels.

Goal: Achieve quantum-accelerated design through **QML–PINN coupling** for alloy phase and defect prediction.

---

### Stream D – Active Learning and Multimodal Integration

_"Closing the loop between AI, experiment, and reality."_

Focus: Federated learning, multimodal data fusion, and closed-loop active learning.

#### Modules
- **D1_MultimodalDataset/** – Curated datasets linking structure, XRD, spectra, micrographs, and process parameters.  
- **D2_ActiveLearning/** – Reinforcement and uncertainty-based experiment selection for robotic thin-film synthesis.  
- **D3_FederatedLearning/** – Privacy-preserving multi-lab data training for cross-institutional model robustness.  
- **D4_Explainability_Robustness/** – Counterfactual and out-of-distribution (OOD) detection tools for explainable materials AI.

Goal: Build an **autonomous materials discovery loop** — model suggests → experiment tests → model refines.

---

## Repository Structure

