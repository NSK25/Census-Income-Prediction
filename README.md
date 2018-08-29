# Census-Income-Prediction


Requirements:
-----------------------------------------------
1. Jupyter Notebook
2. Python 3.6 ( Preferably Anaconda env)
3. Libraries:
	- Numpy
	- Pandas
	- Scikit Learn
	- matplotlib
	- seaborn
	- statistics


Execution:
--------------------------------------------------
1. Extract the zip  file into a single directory. (Make sure dataset and ipynb file are in same directory or might have to reset the path directory)
2. Make sure all libraries are imported.
3. Execute the cells inorder.
4. The project is developed in 2 methods
	-using label encoder
	-using one hot encoding with pd.get_dummies
5. The following are the output metrics:
	- Model Accuracy: Accuracy of the model on training dataset ("adult.csv")
	- Validation Set Accuracy: Accuracy of model on a cross validated testing dataset ("adult.test.csv")

***NOTE***
There might be a small variation in model accuracy each time it is run from outputs mentioned in report because of the randomness of train_test_split()
