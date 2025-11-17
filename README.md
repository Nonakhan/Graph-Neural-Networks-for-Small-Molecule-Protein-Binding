# Graph-Neural-Networks-for-Small-Molecule-Protein-Binding

# Molecular Graphs & Graph Neural Networks (GNNs) — Tutorial Notebook

This repository contains a tutorial-style Jupyter notebook introducing **molecular graphs**, **chemical featurization**, and **graph neural networks (GNNs)** for molecular property prediction.  
It is adapted from a Leash Bio tutorial from the NeurIPS 2024 competiton 'Predict New Medicine with BELKA' and reorganized for clarity, reproducibility, and demonstration purposes.
The original competition can be found here: https://www.kaggle.com/code/agastyapulapaka/leash-tutorial-molecular-graphs-and-gnns

---

## Contents

- **`molecular-gnns.ipynb`**  
  A step-by-step notebook covering:
  - Representing molecules as graphs  
  - Converting SMILES → graph objects  
  - Building datasets of molecules  
  - Constructing a neural message passing network (GNN)  
  - Training and evaluating the model  
  - Visualizing performance and predictions  

---

## Environment Setup

### 1. Clone this repository

```bash
git clone https://github.com/Nonakhan/Graph-Neural-Networks-for-Small-Molecule-Protein-Binding.git
cd molecular-gnns
