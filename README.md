# Protein-Network-Analysis

Residue-level protein network mapper with 2D and 3D visualization, highlighting hubs and bottlenecks using Python, NetworkX, and Py3Dmol.

---

## Overview

This project constructs a **Protein Structure Interaction Network (PSIN)** from a PDB file, where nodes represent residues and edges represent interactions based on a distance cutoff. It calculates network metrics like **degree** and **betweenness centrality**, and highlights key residues in both **2D network plots** and **3D protein structure visualizations**.

---

## Features

- Build residue interaction networks from any PDB structure.
- Compute **network centrality metrics** (degree, betweenness).
- Visualize the protein network in **2D** with top residues highlighted.
- Map hubs and bottlenecks directly on the **3D protein structure**.
- Fully reusable by simply changing the PDB ID.

---

## Installation

1. **Clone the repository:**

```bash
git clone https://github.com/YOUR_USERNAME/Protein-Network-Analysis.git
cd Protein-Network-Analysis
