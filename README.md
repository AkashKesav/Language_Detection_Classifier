# Language_Detection_Classifier
This repository contains the code for a language detection program, which leverages Hugging Face's transformers library for natural language processing (NLP) tasks. The primary objective of this program is to detect the language of a given sentence.
# Table of Contents
* Introduction
* Module Used
* Model Architecture
* Training
* Evaluation
* Contributions and Acknowledgements
# Datasets
The dataset used for this project is available on Kaggle
# Models Used
This project uses the BERT Base multilingual uncased model from Hugging Face's transformers library
# Model Architecture
The model architecture centers around the BERT (Bidirectional Encoder Representations from Transformers) model, which has been fine-tuned specifically for the task of language classification.
# Training
To train the model, follow the steps provided in the notebook sequentially. This process includes loading the dataset, creating a language_dict, preprocessing the data (including tokenization and encoding), configuring the model architecture, and executing the training loop.
# Evaluation
The evaluation metrics used in this project are accuracy and loss. After training, the model's performance is assessed on a separate test set to ensure it generalizes well to unseen data.
# Contributions and Acknowledgements
Contributions are highly encouraged! If you have suggestions for improvements or find any issues, please open an issue or submit a pull request. Special thanks to Hugging Face for their transformers library and to the creators of the dataset used in this project.

