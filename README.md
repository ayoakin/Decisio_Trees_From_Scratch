# Decision Trees From Scratch


## Project Overview
This project recreates 4 Decision Trees algorithms from scratch - ID3, C4.5, CART and CHAID. It then compares it to the SKlearn Decision Tree regressor and classifier implementation. The custom models created can perform both regression and classification tasks. TThe dataset used for classification is the Iris dataset. The Iris dataset is a popular dataset containing sepal length, width and petal length, width for 3 different types of irises' (Setosa, Versicolour, and Virginica) stored in a 150x4. Each type of irises has 50 instances in the dataset. The dataset used for regression is the California Housing Dataset. The dataset contains containing 20,640 samples and 8 features. All features are numerical features and encoded as floating numbers. The code uses the Sklearn library to import and split the datasets into a train and test set.

Recreating these Decision Tree algorithms provides insights into

* Each's unique offering and how they differ 
* Strenghts and Drawbacks of the each algorithm
* Customization potential and Use cases for the algorithms

For a detailed explanation on these, check out the accompanying [article on medium](https://medium.com/@ayoakinkugbe/build-k-nearest-neighbors-knn-from-scratch-10dbc5b21254)

### Code
You can find the code for this project [here](https://github.com/ayoakin/Decision_Trees_From_Scratch/blob/main/Decision_Trees_From_Scratch.ipynb).

File overview:

* `Decision_Trees_From_Scratch.ipynb` - the full code from this project


## Environment Setup

### Installation
To follow this project, please install the following locally:

* Python 3.8+
* Python packages
  * pandas
  * numpy
  * scikit-learn
  * Matplotlib

### Data

The datasets used for this implementation are
* the Iris dataset originally on [Scikit-learn](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html).
* the California housing dataset originally on [Scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html).
