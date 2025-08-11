# Legal-Named-Entity-Recognition-NER-BERT-Base-Cased
This project fine-tunes a BERT Base Cased model for Named Entity Recognition (NER) on legal text. It identifies and labels entities such as PERSON, ORG, DATE, and PROVISION in legal documents using the Hugging Face Transformers library and Gradio for an interactive web UI. 

Label Entities:
PERSON – Names of individuals mentioned in legal documents (e.g., parties, judges, witnesses).
ORG – Names of organizations, companies, government bodies, or institutions involved in the case.
DATE – Specific dates relevant to the legal matter (e.g., filing date, hearing date, contract date).
PROVISION – Names or references to legal statutes, acts, codes, or regulations.

🔹 Key Features
Model: bert-base-cased fine-tuned for token classification
Entities Extracted: PERSON, ORG, DATE, PROVISION
Dataset Format: Entity-per-row CSV with sentences and labels
Interactive UI: Gradio interface for real-time entity extraction
Evaluation Metrics: Precision, Recall, F1-score, Accuracy via SeqEval

🔹 Tech Stack
Python 3.10+

Hugging Face Transformers

PyTorch

Datasets (Hugging Face)

SeqEval for NER evaluation

Pandas, NumPy

Gradio for deployment
