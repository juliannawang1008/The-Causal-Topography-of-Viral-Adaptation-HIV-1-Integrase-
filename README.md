# The Causal Topography of Viral Adaptation (HIV-1 Integrase)

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![R Minimum Version](https://img.shields.io/badge/R-%3E%3D%204.2.0-brightgreen)
![Data](https://img.shields.io/badge/Data-Open_Access-orange)
![Status](https://img.shields.io/badge/Status-Publication_Ready-success)

## 📌 Overview
This repository contains the complete computational architecture, mathematical modeling pipelines, and feature metadata used to systematically decouple lineage-intrinsic evolutionary trajectories from drug-induced selective pressures in HIV-1 integrase. By deploying a Dual-Track Bayesian network framework across 2,044 curated sequences, we decoded the highly divergent evolutionary causal highways separating CRF01_AE and BC-related lineages under identical INSTI pressure, unraveling the mechanisms of Evolutionary Canalization and Spatial Architectural Recalibration.

## 🧬 Analytical Pipeline (Complete Flowchart)

Our methodology fundamentally transitions from traditional mutation-counting to high-dimensional predictive algorithmics. The full bioinformatics pipeline is mapped below:

```mermaid
graph TD
    A[Raw Combined Dataset: n=2,073] --> B{Stage 1: Genomic Sanitization}
    B -- Excluded: Stops, Gaps --> C[Stage 2: Metadata Verification]
    C --> D[Quality-Controlled Dataset: n=2,044]
    
    D --> E{Stage 3: Dual-Track Divergence}
    
    E -->|Track A| F[Bio-Reality Trace: Quasispecies mixtures retained]
    E -->|Track B| G[Topological Trace: Binary ambiguity resolution]
    
    %% Downstream Analysis part (Added)
    F --> H{Track A Analysis: Localization & Capacities}
    G --> I{Track B Analysis: Epistasis & Causality}
    
    H --> J[Univariate Haldane-Anscombe Enrichment <br> ➔ Figure 1: Adaptive Landscape]
    H --> K[Motif Clustering & Capacity Limits <br> ➔ Figure 4 & Figure 5]
    
    I --> L[Undirected Network Topology GLasso-STARS <br> ➔ Figure 2: Epistatic Co-occurrence]
    I --> M[Directed Causal Kinetics Bayesian DAGs <br> ➔ Figure 3: Causal Relays]
