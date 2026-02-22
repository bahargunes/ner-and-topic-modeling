# Named Entity Recognition (NER) and Topic Modeling

This project includes two main tasks: training a Named Entity Recognition (NER) model and performing topic modeling on customer reviews.

## Features
- **NER Model**:
  - **Dataset**: CoNLL-2003 NER dataset.
  - **Model**: Conditional Random Fields (CRF).
  - **Feature Extraction**: Includes token-level, context-level, and linguistic features.
  - **Class Imbalance Handling**: Implements class weights to address imbalance issues.
  - **Evaluation**: Precision, recall, and F1-score metrics.

- **Topic Modeling**:
  - **Dataset**: Amazon reviews for a leading phone brand (`K8 Reviews v0.2.csv`).
  - **Analysis**: POS tagging, lemmatization, and topic modeling using Latent Dirichlet Allocation (LDA).
  - **Visualization**: Word clouds for topics.
  - **Evaluation**: Coherence score (c_v metric) to measure topic quality.

## Project Structure
- `e2521649_phase1.ipynb`: Contains the implementation of the NER model, including data preprocessing, feature extraction, model training, and evaluation.
- `e2521649_phase2.ipynb`: Implements topic modeling on customer reviews, including text preprocessing, POS tagging, lemmatization, and LDA-based topic modeling.

## Results
- **NER Model**: Achieves competitive precision, recall, and F1-scores across various entity types. Class imbalance issues are addressed using weighted class adjustments.
- **Topic Modeling**: Identifies key topics in customer reviews, evaluates coherence scores, and visualizes topics using word clouds.