# Modeling the Electrical Conductivity of Nanocomposites  
*A combined qualitative and quantitative simulation project*

## 📌 Overview
This project analyzes how conductive nanofillers (e.g., carbon nanotubes, graphene, metallic nanoparticles) dispersed within an insulating polymer matrix contribute to overall **electrical conductivity**. It uses two complementary Jupyter Notebooks:

1. **Qualitative Model** – explores physical mechanisms and conceptual behavior  
2. **Quantitative Model** – implements numerical simulation and conductivity prediction

Together, they provide a complete understanding of filler dispersion, percolation behavior, and transport mechanisms in polymer nanocomposites.

---

## 📁 Repository Structure
```
├── Qualitative_model_for_electrical_conductivity.ipynb
├── quantitative_model_for_electrical_conductivity.ipynb
└── README.md
```

---

## 🧪 1. Qualitative Model – Conceptual Understanding
This notebook explains the key scientific principles that govern electrical conductivity inside nanocomposite materials:

### ✔ Percolation Theory
- How conductive pathways form when filler loading exceeds a critical volume fraction (ϕc).  
- Behavior of conductivity near percolation:
  σ = σ₀ (ϕ − ϕc)ᵗ

### ✔ Tunneling & Hopping Mechanisms
- Electrons pass between fillers separated by nanoscale gaps.  
- Impact of tunneling distance, barrier height, and dispersion quality.

### ✔ Network Formation
- Filler alignment, aspect ratio, and clustering  
- Why CNTs and graphene provide high conductivity at low loading

This notebook builds intuition and visually explains how nanocomposite conductivity emerges.

---

## 🧮 2. Quantitative Model – Simulation & Calculation
This notebook implements numerical methods to compute and simulate conductivity, including:

### ✔ Percolation-Based Conductivity Model
- Calculates conductivity vs. filler volume fraction  
- Estimates percolation threshold & scaling behavior

### ✔ Effective-Medium Approximation (EMA)
- Computes composite conductivity based on matrix + filler properties

### ✔ Tunneling Resistance Model
- Models electron tunneling probability  
- Uses exponential decay approximation:  
  Rₜ ∝ exp(βd)

### ✔ Visualization
- Conductivity–volume fraction curves  
- Identification of conducting vs. insulating regimes

---

## 📈 Applications
- Designing materials for **EMI shielding**, **sensors**, **conductive films**, **batteries**  
- Studying CNT/graphene filler effects  
- Predicting threshold behavior for engineering & research

---

## 🚀 How to Use
Install dependencies:
```
pip install numpy scipy matplotlib
```

Open notebooks:
```
jupyter notebook
```

1. Run **Qualitative model notebook** → understand theory  
2. Run **Quantitative model notebook** → generate conductivity plots

---

