# Week 3 - Halfday 5

## Missions & Activities:

### Activity 1
- **Problem**: Find the best hyperparameters for SVM using Genetic Algorithms (GA).
- **Hint**: Consider which metrics to use when comparing GA with grid search. The comparison should not be limited to classification performance metrics.
- **Tools**: DEAP or pure Python.

### Activity 2
- **Weekly Evaluation (Grade 1-6)**: This evaluation will be based on:
  - the code provided at the end of the week (activity 2), including your comments. The code should integrate GA in your SVM application. Add markdown cells at the end of the notebook to address the questions below.
  - questionnaire concerning the theorethical concepts investigated this week

## Expected Outcomes:
- **Activity 2**: An updated Jupyter notebook that includes the implementation of GA for hyperparameter tuning in SVM.
- **Activity 3**: A grade reflecting the student’s understanding and application of the concepts.

## Tasks – Classification and Model Tuning Using SVM and GA

1. **Improve your SVM code**: Import your old jupyter notebook. Implement the suggestions you received during from the peer reiew. *Optionally*, change dataset. Instead of MNIST use the [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html) 
2. **Implement GA**: Use GA to find the best hyperparameters for your SVM developed in week 3, day 1.  
3. **Compare GA’s Performance**: Evaluate the performance of GA versus grid search.

## Questions:
- Is GA performing better than grid search in your case? In what terms? Why?

## Acquired Competences
- **Explore a dataset and properly implement and evaluate a simple classification or regression pipeline using SVM**:
  - Analyze a dataset, including feature extraction, correlation analysis, and handling of missing values.
  - Preprocess a dataset appropriately for classification or regression using SVM.
  - Implement a Genetic Algorithm to search for the quasi-optimal solution of an optimization problem.

---

## OPTIONAL Content for Halfday 5

### Missions & Activities:
### Optional Activity
- **Problem**: *Discover and Implement One-Class SVM* - Explore the concept of One-Class SVM and its applications.
- **Tools**: -
- **New/Consolidation of ML Glossary**: One-Class classification (SVM).


1. **Understanding One-Class SVM**:
- Understand suitable applications for One-Class SVM.
- Learn how One-Class SVM works.
- Choose a class from the provided dataset and implement One-Class SVM.
- Comment on the results step by step.

2. **Implementation of One-Class SVM**:
- Test multiple kernels on simple dataset for [anomaly detection](https://scikit-learn.org/stable/auto_examples/applications/plot_outlier_detection_wine.html#sphx-glr-auto-examples-applications-plot-outlier-detection-wine-py)
- Find the best hyperparameters for SVM (note: hyperparameters depend on the kernel used).
- Evaluate the performance on a test set:
  - Confusion matrix, accuracy, precision, F1-score.
  - Plot the learning curve.
  - Compare with previous results and estimate the contribution of feature engineering.
    - Plot confidence intervals.

### Questions:
- Why the heck is a One-Class classifier necessary?
- How can SVM help to deal with the problem?

## Acquired Competences
- **Implement a simple SVM**:
  - Understand the concept of a kernel in SVM, the kernel trick, and key hyperparameters.
  - Explain and apply SVM for one-class, two-class, and multi-class classification.



