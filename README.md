# VSA-Research
VSA Research Summer 2018

## About the Code
This repository is for the Virtual Student Advisor Project. The code is run in Jupyter Notebook. Each notebook has more extensive documentation inside, explaining why I choose certain values or particular functions.

## Dataset Files
### For classification
1. VSA_new_total – non-normalized dataset
2. VSA_new_norm – normalized dataset
3. VSA_norm_reduced – Reduced normalized
4. VSA_labels – The target score for the above datasets
### For NLP
1. studyplan_document.txt – The study plan represented as a document.
2. studyplan_sentences – PlanIDs mapped to study plan sentence representations as described in the main document
## Code Files
1. Decision Tree Classification.ipynb – Code for how I used various decision tree classifiers
2. Neural Network Binary Classifier.ipynb – Code for how I classified using a Neural Network
3. PCA.ipynb – Code for how I performed PCA
4. Preprocessing for Classification.ipynb – Code for how I preprocessed the original files
5. Sentence Vectors.ipynb – Creates one-hot-encoded sentence vectors
6. LSTM – Has the (currently testing) LSTM model. Does not work at all.
## Code File running order
Please run the code files in this order so that the files used in the code may be created:
1.	Preprocessing for Classification
2.	PCA
3.	Any classifier file (either neural network or decision tree)
4.	Any NLP file
