# NLP Assignments

## Part 1 - FFNN for NER Tagging

### Description
We implement a Feedforward Neural Network (FFNN) model for Named Entity Recognition (NER) tagging. The goal is to predict the NER tags (e.g., PERSON, ORGANIZATION, LOCATION) for each word in a given sentence.

### Implementation
- We use a single hidden layer FFNN architecture.
- The model is trained using the provided training dataset and evaluated on the validation dataset.
- Hyperparameters:
  - Hidden Layer Dimension: 256
  - Activation Function: ReLU
  - Batch Size: 512
  - Number of Epochs: 15
  - Learning Rate: 0.001
  - L2 Regularization: 1e-05

### Results
- The model achieves an accuracy of approximately 96% on the validation set.

## Part 2 - LSTM for NER Tagging

### Description
In this assignment, we implement a Long Short-Term Memory (LSTM) model for Named Entity Recognition (NER) tagging. The goal is to predict the NER tags (e.g., PERSON, ORGANIZATION, LOCATION) for each word in a given sentence.

### Implementation
- We use a bidirectional LSTM architecture.
- The model is trained using the provided training dataset and evaluated on the validation dataset.
- Hyperparameters:
  - Embedding Dimension: 64
  - Hidden Dimension: 128
  - Batch Size: 512
  - Number of Epochs: 15
  - Learning Rate: 0.005
  - L2 Regularization: 1e-06

### Results
- The model achieves an accuracy of approximately 97% on the validation set.

## Conclusion
Both the FFNN and LSTM models show promising results for NER tagging. The LSTM model slightly outperforms the FFNN model, which is expected due to its ability to capture long-range dependencies in the input sequence. These models can be further improved with hyperparameter tuning and more complex architectures.

