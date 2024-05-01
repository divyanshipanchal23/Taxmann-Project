# Ticket Priority Classification

## Overview

This project aims to classify ticket priority based on the ticket description. It utilizes natural language processing (NLP) techniques and machine learning algorithms to predict the priority level of support tickets automatically.

## Dataset

The dataset used in this project consists of support tickets collected from our customer support system. Each ticket contains the following information:

- Ticket ID
- Customer Name
- Customer Email
- Customer Age
- Customer Gender
- Product Purchased
- Date of Purchase
- Ticket Type
- Ticket Subject
- Ticket Description
- Ticket Status
- Resolution
- Ticket Priority
- Ticket Channel
- First Response Time
- Time to Resolution
- Customer Satisfaction Rating

## Preprocessing

- Text data preprocessing: Lowercasing, removing punctuation, and tokenization of ticket descriptions.
- Encoding categorical variables: Ticket priority and ticket channel are encoded using label encoding.

## Model

- The model architecture consists of an embedding layer, LSTM layer, and dense layers.
- The model is trained using the Adam optimizer and binary cross-entropy loss function.
- Hyperparameters such as embedding dimension, LSTM units, and dropout rates are tuned to improve performance.

## Evaluation

- The model is evaluated on the test set using metrics such as loss and accuracy.
- Further analysis is conducted to identify areas for improvement and fine-tune the model.

## Next Steps

- Experiment with different model architectures and hyperparameters to improve performance.
- Explore advanced NLP techniques such as word embeddings and attention mechanisms.
- Deploy the model in a production environment for real-time ticket classification.

## Contributors

- Divyanshi Panchal 11021210044
- Sagnik Chowdhury 10321210120

## License

This project is licensed under the MIT License
