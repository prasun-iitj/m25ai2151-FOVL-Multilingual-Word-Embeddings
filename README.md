# M25AI2151 — FOVL Multilingual Word Embeddings

Course assignment at IIT Jodhpur.

## Project
Training and evaluating 300-dimensional FastText Skip-gram word embeddings from scratch for seven Indian languages: Hindi, Gujarati, Marathi, Punjabi, Tamil, Telugu, and Urdu.

## Method
- Training corpus: IndicCorpV2-5k
- Model: Gensim FastText (Skip-gram)
- Vector dimension: 300
- Evaluation: Word Similarity Datasets for Indian Languages using cosine similarity and Spearman correlation
- FastText character n-grams support out-of-vocabulary vector generation.

## Main artifact
The final Jupyter notebook and report are intended to be stored in the `notebook/` and `report/` folders.

## Reproducibility
Open the notebook in Google Colab or Jupyter and follow its setup and execution cells. It contains the data loading, preprocessing, training, evaluation, and visualization workflow.

## Author
Prasun Kumar Tripathi  
Roll No.: M25AI2151  
IIT Jodhpur

## Data and attribution
The training corpus is IndicCorpV2-5k. Evaluation uses the Word Similarity Datasets for Indian Languages (Akhtar et al., 2017). Refer to the notebook and report for complete references and experimental details.
