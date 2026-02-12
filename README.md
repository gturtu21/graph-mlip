# Graph-MLIP: Learning Graph Neural Networks for Molecular Potentials

This repository collects structured learning notebooks and examples on **PyTorch**, **PyTorch Geometric (PyG)**, and **e3nn**, following a roadmap towards **Machine Learning Interatomic Potentials (MLIPs)**.

It is designed as a **learning and reference hub** for researchers and engineers interested in **graph-based models for molecular systems**. Most of the notebooks are not made by me and you will find references to the authors in each notebook. I will add extra material and personal notes based on my background on them.

---

## Roadmap

The learning path progresses through four stages:

1. **PyTorch Basics & Advanced** (`pytorch/`)
   - Tensors, autograd, neural networks
   - Custom layers, loss functions, training loops

2. **PyTorch Geometric (PyG)** (`pyg/`)
   - Graph representations, GCNs, GATs
   - Node and edge prediction tasks

3. **Equivariant Neural Networks (e3nn)** (`e3nn/`)
   - Spherical harmonics, equivariant convolutions
   - Building E(3)-equivariant models

4. **Machine Learning Interatomic Potentials (MLIP)** (`mlip/`)
   - Linking learned representations to molecular simulations
   - Training MLIPs with e3nn-based embeddings

---

## Installation

No installation needed. Read the section below

## Running the Notebooks

No installation is required. Each notebook is designed to be run **directly on [Google Colab](https://colab.research.google.com/)**.  

Every notebook contains an **installation cell at the top** to install the necessary dependencies automatically.  

Just open the notebook in Colab and run the cells from top to bottom.


