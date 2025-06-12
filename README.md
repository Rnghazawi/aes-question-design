# Chapter 3: CNN + BERT for Practical Validation of Essay Question Criteria

This repository contains the implementation of an experiment presented in Chapter 3 of a PhD thesis. The experiment investigates how the design of essay questions impacts the performance of Automated Essay Scoring (AES) systems, specifically using a hybrid model that combines BERT embeddings with a Convolutional Neural Network (CNN) classifier.

## 🧪 Objective

The goal of this experiment is to practically validate the effectiveness of the proposed criteria for essay question design by comparing performance across essay sets using a BERT-CNN model. The assumption is that better-designed essay prompts will yield more predictable and scorable responses.

## 🧠 Model Overview

- **BERT** is used as the feature extractor to generate contextual embeddings for essay inputs.

- **CNN** is applied on top of BERT embeddings to capture local text patterns and perform classification.

## 📁 Files

Chapter3_CNN_BERT_Criteria_Validation.ipynb: The Jupyter notebook containing the full experiment.

<!-- Chapter3_CNN_BERT_Criteria_Validation.py: The script version for easy readability and modular editing. -->

## ▶️ How to Run

## 1. Install Required Packages
```bash
pip install torch transformers pandas numpy scikit-learn
```
## 2. Run the Notebook

Use Jupyter:
```bash
jupyter notebook Chapter3_CNN_BERT_Criteria_Validation.ipynb
```
<!--
Or execute the Python script:

python Chapter3_CNN_BERT_Criteria_Validation.py -->

# 📊 Output

- Accuracy, F1 score, and Quadratic Weighted Kappa (QWK)

- Confusion matrix

- Graphs for training/validation performance

# 📌 Notes

- Essay data must be preprocessed to match BERT tokenisation requirements.

- Ensure you load the correct version of BERT via Hugging Face.


📞 Contact

For questions or collaboration: **Rayed Ghazawi**\
PhD Candidate, University of Bristol\
Email: [rnghazawi@uqu.edu.sa]

