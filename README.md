📌 Project Title

Date Fruit Classification using Artificial Neural Network (PyTorch)

📖 Overview

This project builds an Artificial Neural Network (ANN) using PyTorch to classify different types of date fruits based on their features.

The model learns patterns from the dataset and predicts the correct fruit class with high accuracy.

📊 Dataset

  -  Dataset: DateFruit_Dataset.csv
  -  Multi-class classification problem
  -  Target column: Class

⚙️ Tech Stack
  - Python
  - Pandas, NumPy
  - Scikit-learn
  - PyTorch

🔄 Workflow

1. Data Preprocessing
  - Train-test split (80/20)
  - Label Encoding on target variable
  - Feature Scaling using StandardScaler

3. Model Architecture
  - Input Layer → based on feature size
  - Hidden Layer 1 → 64 neurons (ReLU)
  - Hidden Layer 2 → 64 neurons (ReLU)
  - Output Layer → Multi-class output

🧠 Model Training

  - Loss Function: CrossEntropyLoss
  - Optimizer: Adam
  - Epochs: 100
  - Batch Size: 32

📈 Results
  - ✅ Test Accuracy: 92.77%
  - 📉 Final Test Loss: 0.23

🔍 Key Learnings
  - Importance of feature scaling in neural networks
  - Handling multi-class classification using CrossEntropyLoss
  - Difference between training loss and test loss
  - Working with PyTorch DataLoader and TensorDataset

📌 Future Improvements

  - Add Dropout for regularization
  - Hyperparameter tuning
  - Try deeper architectures
  - Add confusion matrix visualization
