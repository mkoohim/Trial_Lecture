# Trial_Lecture - Protein Classification

## 📋 Overview

This repository contains a protein classification pipeline for predicting subcellular localization (Cell Membrane vs Nucleus) using machine learning approaches.

## 📁 Files

- **Protein_Classification_Classical.ipynb** - Google Colab notebook with complete analysis
- **protein_dataset.csv** - Dataset with 2,000 balanced protein sequences

## 🚀 Quick Start

1. Open the notebook in Google Colab: [Protein_Classification_Classical.ipynb](Protein_Classification_Classical.ipynb)
2. Upload `protein_dataset.csv` when prompted
3. Run all cells
4. Wait 5-10 minutes for results

## 🔬 Methods

This notebook implements three feature extraction approaches:

1. **AAC (Amino Acid Composition)** - 20 features
2. **k-mers (Tri-peptides)** - 500 features
3. **ProtVec (Word2Vec embeddings)** - 100 features

Each feature set is evaluated with three classifiers:
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)

**Total**: 9 models

## 📊 Expected Results

| Feature | Best Classifier | Expected F1-Score |
|---------|----------------|-------------------|
| AAC | Random Forest | 0.65-0.75 |
| k-mer | SVM | 0.75-0.85 |
| **ProtVec** | **Random Forest** | **0.80-0.88** |

## 💻 Requirements

- Google Colab (free)
- No GPU needed
- Runtime: 5-10 minutes

## 📈 What You'll Get

- Complete performance metrics (Accuracy, Precision, Recall, F1, AUC)
- 8+ visualizations
- Downloadable results CSV
- Model comparison

## 🎓 Dataset

- **Size**: 2,000 protein sequences
- **Classes**: Cell Membrane (1,000) vs Nucleus (1,000)
- **Balance**: Perfectly balanced
- **Source**: Human proteins from UniProt

## 🔧 Technical Details

- **Random seed**: 42 (for reproducibility)
- **Train/test split**: 80/20 (stratified)
- **Cross-validation**: 5-fold
- **Evaluation**: Multiple metrics with ROC curves and confusion matrices

## 📝 License

This project is for educational purposes.

## 👤 Author

GitHub: [@mkoohim](https://github.com/mkoohim)

---

**Happy protein classification! 🧬🔬✨**

