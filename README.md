# Trial_Lecture - Protein Classification

## 📋 Overview

This repository contains a protein classification pipeline for predicting subcellular localization (Cell Membrane vs Nucleus) using machine learning approaches.

## 📁 Files

- **Protein_Classification_Classical.ipynb** - Google Colab notebook with complete analysis
- **protein_dataset.csv** - Dataset with 2,000 balanced protein sequences

## 🚀 Quick Start

### Open from Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mkoohim/Trial_Lecture/blob/main/Protein_Classification_Classical.ipynb)

### Steps:
1. Click one of the Colab badges above
2. Upload `protein_dataset.csv` when prompted (or use the one from this repo)
3. Run all cells
4. Wait 5-10 minutes for results

## Methods

This notebook implements three feature extraction approaches:

1. **AAC (Amino Acid Composition)**
2. **k-mers (Tri-peptides)** 
3. **ProtVec (Word2Vec embeddings)**

Each feature set is evaluated with three classifiers:
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)


##  Dataset

- **Size**: 2,000 protein sequences
- **Classes**: Cell Membrane (1,000) vs Nucleus (1,000)
- **Balance**: Perfectly balanced
- **Source**: Human proteins from UniProt
