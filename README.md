# Emotion Classification for Russian Text using BERT

This repository demonstrates emotion classification using a BERT-based model for Russian language texts. The model uses the pre-trained DeepPavlov/rubert-base-cased model to classify emotions from textual data.

## Overview
The project is built around a Jupyter Notebook that provides:
- Text preprocessing (cleaning and tokenization)
- Emotion encoding (using LabelEncoder)
- BERT model fine-tuning for emotion classification
- Exploratory Data Analysis (EDA) to visualize data distribution and text characteristics
- Model evaluation using F1-score and classification reports

## Installation

To use this repository, clone it and install the required libraries.

### Clone the repository:
```bash
git clone https://github.com/vozmo/emotion_detection.git
cd emotion_detection
```

### Install dependencies:
```bash
pip install -r requirements.txt
```

## Requirements
- Python 3.x
- PyTorch
- HuggingFace Transformers
- Scikit-learn
- Matplotlib
- Pandas
- tqdm
- WordCloud

## Data

The dataset used for emotion classification is a collection of Russian phrases with corresponding emotion labels. 
To ensure the notebook works correctly:
1. Place a CSV file containing the dataset in the repository directory.
2. Name the file `phrases.csv`.

The dataset must contain at least the following columns:
- `Текст фразы` — the text of the phrases to classify.
- `Эмоция` — the corresponding emotion labels.

If needed, you can replace this dataset with your own while maintaining the same column names.

## Usage

1. Open the Jupyter Notebook (`emotion_classification.ipynb`).
2. Ensure the file `phrases.csv` is in the same directory as the notebook.
3. Run each cell sequentially to preprocess the data, train the model, and evaluate the results.
4. Modify the dataset and experiment with different models for further research.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- DeepPavlov for the pre-trained RuBERT model.
- Hugging Face for the transformers library.
- Scikit-learn for classification metrics.
