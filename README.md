# Decision Tree Implementation
This project provides an recursive implementation of the Decision Tree algorithm using Python.
The purpose of this implementation is to allow you to build a decision tree model from a given dataset and make predictions on new data points.

# Features
* Constructs a decision tree from a training dataset from scratch.
* Supports both categorical and numerical features
* Handles missing values in the dataset
* Performs classification tasks
* Calculates various evaluation metrics such as accuracy, gain ratio(using entropy and split info)
* Visualizes the constructed decision tree by printing the information of each node in a preorder fashion

# Installation
To use this project, you need to have Python 3.x installed on your system. You can clone this repository or download the project files as a ZIP archive.

# Dataset Overview:
* The Iris dataset consists of 150 samples with 4 features: sepal length, sepal width, petal length, and petal width.
* Each sample belongs to one of three classes: setosa, versicolor, or virginica.
* each feature is numeric in nature.

# Load and preprocess the dataset:
* import the iris dataset from sklearn.datasets
* Preprocess the dataset if necessary (e.g., handle missing values, normalize features).
* in case of numeric features you need to define the decision boundaries for the dataset-
  * domain knowledge(number of classes in the dataset)
  * feature distribution(which means analyze the distribution of the input features whether their are clusters or not)
  * Granularity required(whether their is need of more detailed catogrization)

# Split the dataset into training and testing sets:
* Use a suitable method to split your dataset into training and testing sets (e.g., train-test split from scikit-learn).

# Train the decision tree model:
* build tree functions as the classifier in the code
* we call fit function and Pass the training
* each node is printed in preorder fashion, the data printed is-
  * level of the node
  * the count of each class
  * entropy of each node
  * the feature on which the node is to be slpitted and gain ration associated with that split

# Evaluate the model:
* Calculate evaluation metrics(e.g., accuracy, precision, recall)to assess the performance of the model.

# Visualization of the Decision Tree:
* Visualized the decision tree using the graphviz and pydotplus libraries.
* saved the decision tree visualization as a pdf file.



If you find this implementation helpful, consider giving it a star on GitHub and sharing it with others who might benefit from it.

Contributing
Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please open an issue or submit a pull request.

Please ensure that your contributions adhere to the existing coding style and conventions.
