# Protein Structure Prediction Using Novel Machine Learning Techniques for 9-mers

This repository contains the reproducible research code for the project **“Protein Structure Prediction using Novel Machine Learning Techniques for 9-mers Dataset”**, developed as part of *AIT 736 – Applied Machine Learning (DL2)* at George Mason University.

The project investigates protein fragment structure prediction using **9-mer sequences** derived from CullPDB, leveraging **multi-input deep learning architectures** that combine amino acid sequence information with torsion-angle features (φ, ψ). The primary model is an **LSTM-based neural network with dense layers and dropout regularization** to capture sequential and non-linear structural patterns.

---

## 📌 Project Objectives
- Load, preprocess, and analyze a standardized 9-mer protein fragment dataset
- Engineer biologically meaningful features from sequence and torsion angles
- Design and train a deep learning model for protein structure prediction
- Evaluate predictive performance using quantitative metrics and visual analysis
- Provide reproducible experiments suitable for academic publication

---

## 🧬 Dataset

- **Name:** 9mers from CullPDB  
- **Source:** UCI Machine Learning Repository  
- **Link:** https://archive.ics.uci.edu/dataset/866/9mers+from+cullpdb  
- **DOI:** 10.24432/C58024  

### Dataset Description
- ~158,000 protein fragments (9-mers)
- Derived from 3,733 non-redundant proteins
- No missing values

**Features per sample:**
1. Amino acid sequence (9 residues)
2. Secondary structure labels (9)
3. Phi (Φ) torsion angles ∈ [-π, π)
4. Psi (Ψ) torsion angles ∈ [-π, π)

⚠️ **Dataset is NOT included in this repository.**  
Please download it directly from UCI https://archive.ics.uci.edu/dataset/866/9mers+from+cullpdb
