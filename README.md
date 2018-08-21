# VSA-Research
VSA Research Summer 2018

About the Code
The code is run in Jupyter Notebook. Each notebook has more extensive documentation inside, explaining why I choose certain values or particular functions.

## Dataset Files
### For classification
  •	VSA_new_total – non-normalized dataset
  •	VSA_new_norm – normalized dataset
  •	VSA_norm_reduced – Reduced normalized
  •	VSA_labels – The target score for the above datasets
### For NLP
  •	studyplan_document.txt – The study plan represented as a document.
  •	studyplan_sentences – PlanIDs mapped to study plan sentence representations as described in the main document
## Code Files
  •	Decision Tree Classification.ipynb – Code for how I used various decision tree classifiers
  •	Neural Network Binary Classifier.ipynb – Code for how I classified using a Neural Network
  •	PCA.ipynb – Code for how I performed PCA
  •	Preprocessing for Classification.ipynb – Code for how I preprocessed the original files
  •	Sentence Vectors.ipynb – Creates one-hot-encoded sentence vectors
  •	LSTM – Has the (currently testing) LSTM model. Does not work at all.
## Code File running order
Please run the code files in this order so that the files used in the code may be created:
1.	Preprocessing for Classification
2.	PCA
3.	Any classifier file (either neural network or decision tree)
4.	Any NLP file
