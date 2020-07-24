1. The training set was split in a ratio of 8:2(4:1) as mentioned for training and validation set.
2. SelectKBest is a feature selection technique used to select the highest 'k' features. It removes all but the 'k' highest scoring features. It returns 'pvalues'(score) for every feature.
3. Custom-built neural network was used to predict and test on the dataset.
4. The maximum accuracy achieved is 93.73
5. The model is already saved as 'my_model' if you want to predict on the testing set without running the entire code. You just have to run the last two blocks in that case.
6. Preferably use jupyter notebook or Google colab to run the python notebook file.
7. To install the dependencies use :
	'sudo python3 -m pip install -r requirements.txt'
