This repository contains Python code implementing Decision Tree and Random Forest classifiers using scikit-learn.

Decision Tree:
The Decision Tree classifier is applied to a dataset representing tennis play decisions based on weather conditions. It preprocesses the data, including label encoding categorical features, splitting the dataset into training and testing sets, and training the model. The Decision Tree classifier is then used to predict tennis play decisions based on given weather conditions. Additionally, the decision tree structure is visualized using tree.plot_tree.

Random Forest:
The Random Forest classifier is applied to the digits dataset from scikit-learn. It preprocesses the data, splits it into training and testing sets, and trains a Random Forest classifier with 100 decision trees. The model's accuracy is evaluated on the testing set, and a confusion matrix is plotted to visualize the model's performance.

Files:
decision_tree.ipynb: Jupyter Notebook containing code for Decision Tree classifier.
random_forest.ipynb: Jupyter Notebook containing code for Random Forest classifier.
tennis.csv: Dataset used for Decision Tree classifier.
Dependencies:
Python 3.x
NumPy
pandas
Matplotlib
Seaborn
scikit-learn
Usage:
Clone the repository.
Ensure all dependencies are installed.
Run the Jupyter Notebooks (decision_tree.ipynb and random_forest.ipynb) to see the implementation and results.
Contributors:
Mehboob Khan
License:
This project is licensed under the MIT License.

References:
Documentation for scikit-learn: scikit-learn Documentation
Decision Tree classifier: scikit-learn DecisionTreeClassifier Documentation
Random Forest classifier: scikit-learn RandomForestClassifier Documentation



