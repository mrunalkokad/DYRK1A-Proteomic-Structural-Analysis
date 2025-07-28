# 🧬 DYRK1A: Proteomic and Structural Analysis using Biopython

This project focuses on DYRK1A, a dual-specificity tyrosine-regulated kinase implicated in neurodegenerative diseases such as Alzheimer's and Down Syndrome.

Using Biopython and related libraries, the analysis explores sequence-level, structural, and interaction-level properties of the DYRK1A protein (PDB ID: `7O7K`).

## 📌 Objectives

- Analyze amino acid composition and isoelectric point of DYRK1A
- Perform BLAST search to identify homologous proteins
- Visualize protein-protein interaction (PPI) network from STRING
- Analyze structural features of the 3D structure (PDB ID: `7O7K`)
- Generate 3D scatter plots, distance matrices, and Ramachandran plots
- Plot residue-level B-factors, atom frequency, mass distribution
- Extract features using RDKit and run basic ML classification

## 🧪 Protein Analyzed

- **Name**: DYRK1A
- **PDB ID**: 7O7K
- **Function**: Involved in brain development, cell cycle regulation
- **Relevance**: Linked to Down Syndrome, Alzheimer’s, and other neurological disorders
  
## 🧰 Tools & Libraries

- 🐍 Python
- 🧪 [Biopython](https://biopython.org/)
- 🧬 NCBI BLAST
- 📊 Matplotlib, NetworkX, Plotly
- 🧠 RDKit (for chemical descriptors)
- 🧠 scikit-learn (for ML classification)
- 🧫 STRING Database API (for PPI)

## 🔍 Major Steps

1. Protein Analysis
   - Amino acid composition
   - Isoelectric point calculation
2. Homology Search
   - BLAST search for similar sequences
   - Network graph of top hits
3. Structural Bioinformatics
   - Residue and CA atom 3D visualization
   - Ramachandran plot
   - Hydrophobicity distribution
   - B-factor and residue mass plots
   - Distance matrix
4. Machine Learning
   - Feature extraction using RDKit
   - Random Forest classification

## 🧠 Biological Relevance
DYRK1A is a critical protein that regulates multiple signaling pathways in the brain. Overexpression or mutations are associated with:
1. Down Syndrome
2. Alzheimer’s Disease
3. Autism Spectrum Disorders
4. Neurogenesis and synaptic plasticity dysfunction

This project offers insights into its sequence and structural conservation, which can help in target discovery and drug development.

## 📊 Key Visual Outputs

- Amino acid composition bar chart
- BLAST top-hits graph
- Ramachandran plot
- 3D scatter of alpha-carbon atoms
- Distance matrix heatmap
- Hydrophobicity plot
- Average B-factor per residue
- Atom type frequency
- Residue mass distribution

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/DYRK1A-Proteomic-Structural-Analysis.git
   cd DYRK1A-Proteomic-Structural-Analysis

2. Initial dependencies:
   pip install -r requirements.txt

3. Run the script:
   python proteinwork.py
