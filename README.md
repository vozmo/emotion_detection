# emotion_detection
Emotion Classification for Russian Text using BERT This repository contains a Jupyter notebook for emotion classification on Russian text. The model is based on DeepPavlov's RuBERT and is trained to classify emotions using labeled text data. The repository includes data preprocessing, model training, evaluation, and exploratory data analysis (EDA).

___

# Emotion Classification for Russian Text using BERT

This repository demonstrates emotion classification using a BERT-based model for Russian language texts. The model uses the pre-trained `DeepPavlov/rubert-base-cased` model to classify emotions from textual data.

## Overview
The project is built around a Jupyter Notebook that provides:
- **Text preprocessing** (cleaning and tokenization)
- **Emotion encoding** (using LabelEncoder)
- **BERT model fine-tuning** for emotion classification
- **Exploratory Data Analysis (EDA)** to visualize data distribution and text characteristics
- **Model evaluation** using F1-score and classification reports

## Installation

To use this repository, clone it and install the required libraries.

### Clone the repository:
```bash
git clone https://github.com/vozmo/emotion_detection.git
cd emotion_detection
