# Financial Sentiment Analysis with FinBERT

This project aims to perform financial sentiment analysis using FinBERT, a BERT-based model pre-trained for financial texts. The model is fine-tuned on the SENTFIN dataset, which focuses on entity-level sentiment.

Features:

Preprocessing: Cleaned and prepared financial text data.
FinBERT: Fine-tuned the model for entity-specific sentiment classification.
Evaluation: Achieved improved sentiment prediction accuracy through multiple fine-tuning steps.

# Model Architecture

Pretrained Model: FINBERT, a BERT variant specialized for financial language understanding.
Fine-tuning: The model is fine-tuned using the SENTFIN dataset to improve performance on financial sentiment tasks.


# Updates:

Layer freezing and unfreezing to preserve pretrained knowledge while adapting to new data.

Added layers and different activation functions.

Hypertuning hyperparameters such as learning rate, batch size, and the number of epochs to optimize performance.
Results

# Coclusion

The fine-tuned FINBERT model achieved an improved accuracy of 86.7%, up from 68% with the initial setup.
