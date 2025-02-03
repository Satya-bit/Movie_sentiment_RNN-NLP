# Movie_sentiment_RNN-NLP
This project aims to give the sentiment of the movie review using RNN.

IMDB dataset was used for this. Total number of rows is 50000.

After text preprocessing and cleaning RNN model was applied.

# Model Structure

Embedding Layer:

Converts input words into dense vector representations of size 128.
This layer is trainable, meaning the embeddings are learned along with the model.
Simple RNN Layer:

Contains 128 units with ReLU activation.

Processes sequential text input by capturing temporal dependencies in the data.

Dense Output Layer:

Uses a sigmoid activation function to output a probability score, making it suitable for binary classification tasks.

Model Compilation

The model is compiled using:

Loss Function: Binary cross-entropy, as the task involves binary classification.

Optimizer: Adam optimizer for adaptive learning rate adjustments.

Metric: Accuracy to evaluate model performance.

Using streamlit a webapp was made.

![image](https://github.com/user-attachments/assets/00a8e532-c0fe-489c-bee9-28c8ebafb525)
