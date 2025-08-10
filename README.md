# Rice Type Classification with PyTorch

This repository contains a complete deep learning workflow for **classifying rice grain types** using the [Rice Type Classification dataset](https://www.kaggle.com/datasets/mssmartypants/rice-type-classification).  
The model is implemented with **PyTorch** and trained on numerical features after preprocessing and normalization.

---

##  Features
- **Automatic Dataset Download** from Kaggle using [`opendatasets`](https://github.com/JovianML/opendatasets)
- **Data Preprocessing**:
  - Remove missing values
  - Drop irrelevant columns
  - Normalize features to [-1, 1] range
- **Visualization**:
  - Scatter plots
  - Feature histograms
  - Training/validation loss and accuracy curves
- **Model**:
  - Fully connected feed-forward neural network
  - Custom `Dataset` and `DataLoader` classes
  - Training, validation, and testing loops
- **Evaluation**:
  - Accuracy score
  - Loss plots
  - Predictions vs actual labels visualization


