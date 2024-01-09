# BioNER (Biomedical Named Entity Recognition) Project Named Entity recognition using BioRed dataset
## Overview
This repository contains my attempt to solve the Named Entity Recognition (NER) task on the BioRed dataset using a Convolutional Neural Network (CNN) implemented with the spaCy library. <br>
The project explores various experiments, including preprocessing steps such as lemmatization and stemming, aimed at improving the model's performance. Additionally, I have considered potential experiments involving transformer architectures and exploring the impact of weighted loss.<br>
In the project, there is a starting point to perform "Relation Extraction".

## Experiments to imporve the model
1. Lemmatization and Stemming
In the pursuit of better model performance, I experimented with lemmatization and stemming as preprocessing techniques.

## Possible experiments to improve the model
### Transformer Architecture
There's an ongoing exploration of the transformer architecture for NER. Check the experiments/transformer_experiment.ipynb notebook for details.

### Weighted Loss
Experimented with different loss weightings to assess their impact on model training and performance.

## Notebook usage
- If using Google Colab:
  - Open the notebook <i>NER.ipynb</i> in Google Colab.
  - Follow the instructions within the notebook.

- If running locally:
  - Open the notebook <i>NER.ipynb</i>.
  - Modify only the first setting path in the notebook to match your local file paths.

