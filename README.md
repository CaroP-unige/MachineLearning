# Lab 2 – Linear Regression

This branch contains the implementation and report for Lab 2: Linear Regression, part of the Machine Learning course within the Robotics Engineering program.

*🧭 Assignment Objectives*

- Load and explore two real-world datasets

- Fit and evaluate linear regression models

- Analyze model performance across different training and testing subsets

*📁 Datasets*

- Turkish stock exchange dataset: 'turkish-se-SP500vsMSCI.csv'

- Motor Trend Cars dataset: 'mtcarsdata-4features.csv'

*📌 Task Breakdown*

- Task 1 – Data Preparation
  
    - Download and inspect the Turkish stock exchange and MTcars datasets

    - Ensure compatibility with the selected programming environment 

    - Explore data origin and structure

- Task 2 – Fit Linear Regression Models

    - Univariate regression without intercept using the Turkish stock data
  
      - Compare regression lines trained on random 10% subsets of the data
  
    - Univariate regression with intercept using 'mpg' vs 'weight' from MTcars
  
    - Multivariate regression on the full MTcars dataset
  
      - Predict 'mpg' using 'weight', 'hp', and 'qsec'

- Task 3 – Model Testing and Evaluation
  
  - Repeat Tasks 1, 3, and 4 using only 5% of the data for training

  - Evaluate performance by computing the Mean Squared Error (MSE):

    - On training data

    - On remaining 95% of the data (test set)

  - Automate the process and repeat for multiple random splits (e.g., 10 times)

  - Present results in a table or plot, and provide commentary on model generalization and stability
