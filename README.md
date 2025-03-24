The notebook provided shows steps performed in ECG data classification.
Firstly, the data was pre-processed using balancing and augmentation followed by signal filtering using Gaussian filter.
Secondly, the effect of two different approaches (1D-CNN and LSTM-RNN) were investigated in performing beat classification.
Hyperparameters of 1D-CNN model were fine-tuned using Optuna module and was skipped for LSTM-RNN model owing to high compuatational time.
Thereafter, a hybrid CNN-LSTM model was developed to perform classification which achieved overall 95% test accuracy and over 90% for precision, recall and f1-score for all class labels.
