# 04 — Classification I: K-Nearest Neighbors & Decision Trees

**Slides:** `classification-knn-trees.tex` — add your PDF here, e.g.
`classification-knn-trees.pdf`

## What this chapter covers

The first classification algorithms, taught in depth before the "complete"
survey chapter (05) that adds more models.

- What classification is: predicting a category from labeled examples
- Binary vs multi-class classification, with real examples (spam, medical
  diagnosis, credit approval)
- **K-Nearest Neighbors (KNN)**: the "tell me who your neighbors are" idea,
  Euclidean distance, majority voting, and the impact of the parameter K
  (underfitting vs overfitting)
- **Decision Trees**: asking a series of yes/no questions, splitting criteria
  (Gini index, entropy), key hyperparameters (`max_depth`,
  `min_samples_split`)
- Decision boundaries: KNN's smooth curves vs a tree's rectangular splits
- Evaluation metrics: accuracy, the problem of imbalanced classes, confusion
  matrix, precision, recall, F1-score
- A full worked comparison of KNN vs Decision Tree on the Iris dataset,
  including tree visualization and feature importance
- Best practices and how to avoid overfitting for each algorithm

Sets up the model-comparison mindset used again in chapter 05.
