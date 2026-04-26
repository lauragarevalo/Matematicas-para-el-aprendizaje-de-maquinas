# Matemáticas para el Aprendizaje de Máquinas                                                                                                
                                                                                                                                               
  A collection of machine learning exercises developed for the **Mathematics for Machine Learning** course. Each notebook covers a different topic, combining
  mathematical foundations with practical Python implementation.

  ## Notebooks

  | Notebook | Topic | Key Concepts |
  |---|---|---|
  | [Eigenfaces](./Eigenfaces_Laura_García.ipynb) | Dimensionality Reduction | PCA, face recognition, image reconstruction |
  | [Book Exercises](./Ejercicios_libro_Laura_García.ipynb) | Learning Theory | Exercises from *Learning from Data* (Abu-Mostafa et al., 2012) |
  | [SVM Basic](./SVMBasic_Laura_García.ipynb) | Support Vector Machines | Binary classification, linear separability, generalization |
  | [Model Comparison](./Taller_modelos_Laura_García.ipynb) | Supervised Learning | Logistic regression, decision trees, KNN, model evaluation
  

  ---

  ### Eigenfaces
  Loads a dataset of famous people's faces, splits it into training and test
  subsets, and applies PCA over the training set to compute the average face and
  principal components. A new image is then reconstructed through its projection
  onto those components.

  ### Book Exercises
  Selected exercises from:
  > Abu-Mostafa, Y. S., Magdon-Ismail, M., & Lin, H. T. (2012). *Learning from
  > data*. AMLBook.

  ### SVM Basic
  Applies a Support Vector Machine to the **Banknote Authentication Dataset** — a
  binary classification problem to determine whether a bill is genuine or
  counterfeit. The analysis covers:
  - Whether the dataset is linearly separable
  - Whether samples are randomly drawn
  - Sample size required to guarantee generalization
  - Theoretical explanations and empirical evidence of generalization

  ### Model Comparison Workshop
  Compares four supervised learning models on the **Banknote Authentication
  Dataset**:
  - Linear Regression
  - Logistic Regression
  - Decision Trees
  - K-Nearest Neighbors (KNN)

  Models are evaluated and compared in terms of classification performance.

  ---

  ## Technologies

  - Python 3 · Jupyter Notebook
  - NumPy · Pandas · Matplotlib · scikit-learn

