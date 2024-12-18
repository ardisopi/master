# SHAP Explorations for Transformer-based and SetFit Text Classification

Welcome to the repository showcasing the implementation and evaluation of SHAP (SHapley Additive exPlanations) for transformer-based and SetFit-based multilabel text classification. This repository contains key scripts and resources used for my master's thesis, titled **"Exploring SHAP for Explainability in Multilabel, Transformer-based Text Classification: A Practical Evaluation."**

## Overview

This repository highlights:

1. **Model Implementation:** Scripts to train and evaluate transformer-based and SetFit models on the Reuters-21578 dataset.
2. **SHAP Analysis:** Steps to calculate SHAP values and generate explanations for both models.
3. **Visualization Tools:** Code for SHAP visualizations tailored to text classification tasks.

## Files and Structure

- **`BERT_with_SHAP.ipynb`:** 
  - Implements SHAP with BERT-based models for multilabel text classification.
  - Includes preprocessing, tokenization strategies (unigram, bigram, and n-gram), and SHAP value generation.

- **`SetFit_with_SHAP.ipynb`:**
  - Explores SHAP explainability for a SetFit model trained on the Reuters-21578 dataset.
  - Demonstrates the sentence-level embeddings and their effect on SHAP explanations.

## Features

- **Custom Tokenization Strategies:** 
  - Analyze the impact of unigram, bigram, and n-gram tokenization on model performance and SHAP explanations (BERT-based models).
  - Leverage SetFit's contrastive learning for embeddings without manual tokenization.
- **Evaluation Metrics:** 
  - Granularity, consistency, efficiency, and coverage metrics to evaluate SHAP's interpretability.
  - Includes comparisons between SetFit and BERT-based models.
- **Visualizations:** 
  - Generate SHAP text plots, bar plots, and decision plots for insights into model behavior.

## Prerequisites

No separate installation of packages is required. All necessary libraries and dependencies are imported and installed within the scripts themselves. To run the scripts:

1. Ensure you are using a Python environment compatible with Jupyter Notebook or Google Colab.
2. Open the notebooks, and the package installation commands will execute as part of the initial cells.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/ardisopi/master.git
   cd master
   ```

2. Open the notebooks:
   - Use `jupyter notebook` or Google Colab to explore the provided scripts.

3. Run the cells sequentially to reproduce the SHAP analyses and model evaluations.

## Results Summary

The results obtained from this study:
- Highlight SHAP’s ability to interpret transformer-based and SetFit-based models.
- Identify its limitations in terms of computational efficiency and higher-level semantic explanations.
- Demonstrate the unique benefits of SetFit's sentence-level embeddings in generating cohesive explanations.

For detailed findings, refer to the associated thesis document.

## License

This repository is distributed under the MIT License. See `LICENSE` for more information.

## Author

**Ardi Sopi**  
Master's Thesis, Lucerne University of Applied Sciences and Arts  
Email: ardi.sopi@stud.hslu.ch

## Acknowledgments

Special thanks to Dr. Guang Lu and Dr. Furui Cheng for their supervision and guidance throughout this project.
