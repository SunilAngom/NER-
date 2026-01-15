📌 Named Entity Recognition (NER) using spaCy
This project implements a custom Named Entity Recognition (NER) model using spaCy and a manually annotated dataset in IOB format.

📌Overview
The dataset is loaded from a CSV file containing sentence numbers, words, and NER tags.
Data is converted into spaCy’s required training format with correct character offsets.
A pre-trained English model (en_core_web_sm) is fine-tuned on the custom dataset.
The model is trained, saved, and evaluated on a held-out test set.

📌Key Features
Handles IOB tagging (B-, I-, O) with robustness against tagging inconsistencies.
Uses train-test split for evaluation.
Displays training loss per epoch.
Supports inference on new unseen sentences.

📌Technologies Used
Python
spaCy
Pandas
scikit-learn
tqdm

📌Output
Trained NER model saved locally
Entity predictions on custom input text
Simple accuracy-based evaluation on test data
This project demonstrates an end-to-end NER pipeline, including data preprocessing, model training, testing, and evaluation.
