# Trial_Lecture - Protein Classification

## 📋 Overview

This repository contains protein classification projects for teaching AI in life sciences.

---

## 📚 Projects

### Protein Subcellular Localization (Complete Example)

**Notebook**: `Protein_Classification_Classical.ipynb`
**Dataset**: `protein_dataset.csv`

Predicts whether a protein is located in the cell membrane or nucleus using machine learning.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mkoohim/Trial_Lecture/blob/main/Protein_Classification_Classical.ipynb)

**Dataset**:
- 2,000 protein sequences (1,000 per class)
- Classes: Cell Membrane vs Nucleus
- Source: Human proteins from UniProt

---

## 📚 Homework

###  Antimicrobial Peptide Classification (Student Assignment)

**Notebook**: `Antimicrobial_Peptide_Classification.ipynb`
**Dataset**: `antimicrobial_peptide.csv`

Students implement a complete ML pipeline to predict antimicrobial peptides.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mkoohim/Trial_Lecture/blob/main/Antimicrobial_Peptide_Classification.ipynb)

**Dataset**:
- 2,000 protein sequences (1,000 per class)
- Classes: Antimicrobial Peptide (AMP) vs Non-AMP
- Source: Human proteins from UniProt

**Learning Objectives**:
- Understand the antibiotic resistance crisis and importance of AMPs
- Implement three feature extraction methods (AAC, k-mers, ProtVec)
- Train and compare multiple classifiers
- Evaluate models with comprehensive metrics
- Visualize and interpret results

---

## Methods

Both notebooks implement three feature extraction approaches:

1. **AAC (Amino Acid Composition)**
2. **k-mers (Tri-peptides)**
3. **ProtVec (Word2Vec embeddings)**

Each feature set is evaluated with three classifiers:
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)

**Total**: 9 models per project (3 features × 3 classifiers)

## 🛠️ Technical Requirements

**Python Libraries**:
```
pandas, numpy, scikit-learn, matplotlib, seaborn, gensim
```

**Environment**: Google Colab (recommended) or local Jupyter

**Data**: All datasets included in this repository