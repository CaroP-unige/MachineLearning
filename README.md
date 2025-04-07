# Lab 3 – k-Nearest Neighbors (kNN) Classifier

This branch contains the implementation and report for Lab 3: kNN Classifier, assigned as part of the Machine Learning course in the Robotics Engineering program.

*🧭 Assignment Objectives*

- Load and preprocess a suitable classification dataset

- Implement a flexible k-Nearest Neighbors (kNN) classifier

- Evaluate classifier performance across various settings and configurations

- Generate meaningful statistics and visualize results

*📁 Task 1 - Dataset Options*

🔹Large Option – MNIST Handwritten Digits
  
  - 70,000 grayscale images (28×28 pixels) of handwritten digits (0–9)
  
  - Pre-split into:
  
      - 60,000 training samples
  
      - 10,000 test samples


🔸Smaller Option – Wine Dataset

  - 178 observations, 13 chemical descriptors

  - 3 wine classes


*⚙️ Task 2 – Implementing the kNN Classifier*

  - Create a function with the following inputs:
  
    - train_X: (n × d) training data
  
    - train_y: (n × 1) training labels
  
    - test_X: (m × d) test data
  
    - k: number of neighbors
  
    - (Optional) test_y: (m × 1) ground truth labels

  - The function should:
  
    - Validate argument count (nargin)
  
    - Ensure training/test dimensions match
  
    - Check that k > 0 and k ≤ n
  
    - Classify test data according to the kNN rule
  
    - If ground truth is provided, compute and return error rate

*📊 Task 3 – Evaluation and Testing*
  
  - MNIST Evaluation:
    Perform binary classification:
  
    - For each digit (0–9), classify it vs the remaining 9 (e.g., "is it a 1?" vs "not 1")
  
    - Use multiple k values: k = 1, 2, 3, 4, 5, 10, 15, 20, 30, 40, 50
  
    - Suggestion: avoid k values divisible by the number of classes to reduce ties

✅ For each configuration:

  - Compute confusion matrix

  - Derive metrics: accuracy, precision, recall, F1-score

  - Aggregate results (e.g., average and standard deviation or interquartile range)

📈 Present results in:

  - Plots (e.g., accuracy vs k)

  - Tables summarizing classification performance for each digit and k value
