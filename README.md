# Lab 1 – Naive Bayes Classifier

This branch contains the implementation and documentation for Lab 1: Naive Bayes Classifier, part of the Machine Learning course in the Robotics Engineering program.

*📌 Assignment Overview*

- Main objectives:

    - Data preprocessing

    - Implementation of a Naive Bayes classifier

    - Improvement through Laplace (additive) smoothing

*🧪 Description*

In this lab, the goal is to design and evaluate a simple Naive Bayes classifier on a small categorical dataset (the Weather dataset), using Python. The exercise is structured in multiple steps to promote incremental development and understanding of each phase.

- Task 1 – Data Preprocessing
  
    - Download and prepare the Weather dataset and its description.

    - Convert nominal values into numeric form (integers ≥ 1) for MATLAB compatibility.

    - Use pandas in Python for easier data handling.

    - Small dataset: manual verification of results is encouraged.

- Task 2 – Naive Bayes Classifier

    - Develop a function that:

        - Trains a classifier using a training set.

        - Validates on a test set and returns predictions and error rate (if labels are available).

    - Ensure robustness:

        - Input validation

        - Handling datasets with/without target labels

        - Exclude test patterns with unseen attribute values

- Task 3 – Laplace Smoothing
  
    - Modify the classifier to account for unseen combinations using Laplace (additive) smoothing.

    - Incorporate prior information on attribute cardinality.

    - Enhance reliability on small or sparse datasets.
