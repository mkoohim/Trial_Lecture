# Trial_Lecture - Protein Classification

## 📋 Overview

This repository contains protein classification projects for teaching machine learning in bioinformatics.

---

## 📚 Projects

### 1. Protein Subcellular Localization (Complete Example)

**Notebook**: `Protein_Classification_Classical.ipynb`
**Dataset**: `protein_dataset.csv`

Predicts whether a protein is located in the cell membrane or nucleus using machine learning.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mkoohim/Trial_Lecture/blob/main/Protein_Classification_Classical.ipynb)

**Dataset**:
- 2,000 protein sequences (1,000 per class)
- Classes: Cell Membrane vs Nucleus
- Source: Human proteins from UniProt

---

### 2. Antimicrobial Peptide Classification (Student Assignment)

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

## 🔬 Methods

Both notebooks implement three feature extraction approaches:

1. **AAC (Amino Acid Composition)** - 20 features
2. **k-mers (Tri-peptides)** - 500 features (top 500 most common)
3. **ProtVec (Word2Vec embeddings)** - 100 features

Each feature set is evaluated with three classifiers:
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)

**Total**: 9 models per project (3 features × 3 classifiers)

---

## 🚀 Quick Start

### For Students (Assignment):

1. Click the Colab badge for **Antimicrobial_Peptide_Classification.ipynb**
2. Read the problem statement and background
3. Upload `antimicrobial_peptide.csv` when prompted
4. Complete the TODO sections
5. Answer the analysis questions

### For Instructors (Example):

1. Click the Colab badge for **Protein_Classification_Classical.ipynb**
2. Upload `protein_dataset.csv` when prompted
3. Run all cells to see complete implementation
4. Use as reference for students

---

## 📊 Expected Results

| Feature | Expected F1-Score | Runtime |
|---------|-------------------|---------|
| AAC | 0.65 - 0.75 | ~1 min |
| k-mer | 0.75 - 0.85 | ~2 min |
| ProtVec | 0.80 - 0.88 | ~3 min |

**Total Runtime**: ~5-10 minutes (no GPU needed)

---

## 📖 Educational Value

### Why These Projects?

1. **Real-World Relevance**:
   - Antibiotic resistance is a global health crisis
   - Protein localization is fundamental to cell biology

2. **Progressive Learning**:
   - Start with simple features (AAC)
   - Progress to complex embeddings (ProtVec)
   - Compare classical vs modern approaches

3. **Comprehensive Skills**:
   - Data exploration and visualization
   - Feature engineering
   - Model training and evaluation
   - Results interpretation

4. **Reproducible Research**:
   - Fixed random seeds (42)
   - Standardized evaluation
   - Clear documentation

---

## 🎓 For Instructors

### Assignment Structure:

The **Antimicrobial_Peptide_Classification.ipynb** notebook includes:

- ✅ Detailed problem explanation (why AMPs matter)
- ✅ Dataset overview with biological context
- ✅ Clear learning objectives
- ✅ TODO sections for students to complete
- ✅ Analysis questions for critical thinking
- ✅ Grading rubric (optional)

### Suggested Timeline:

- **Week 1**: Introduction to protein sequences and feature extraction
- **Week 2**: Implement AAC and k-mer features
- **Week 3**: Implement ProtVec and train models
- **Week 4**: Evaluation, visualization, and analysis

---

## 📚 References

- **ProtVec**: Asgari & Mofrad (2015) - Continuous Distributed Representation of Biological Sequences
- **UniProt**: Universal Protein Resource database
- **APD3**: Antimicrobial Peptide Database

---

## 🛠️ Technical Requirements

**Python Libraries**:
```
pandas, numpy, scikit-learn, matplotlib, seaborn, gensim
```

**Environment**: Google Colab (recommended) or local Jupyter

**Data**: All datasets included in this repository

---

## 📄 License

Educational use - Free to use and modify for teaching purposes
