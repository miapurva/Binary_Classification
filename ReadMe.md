1. MinMaxScaler is used for pre-processing of data.
2. The training set was split in a ratio of 8:2(4:1) as mentioned for training and validation set.
3. SelectKBest is a feature selection technique used to select the highest 'k' features. It removes all but the 'k' highest scoring features. It returns 'pvalues'(score) for every feature.
4. Custom-built neural network was used to predict and test on the dataset.
5. The maximum accuracy achieved is 89.31%.
6. Preferably use jupyter notebook or Google colab to run the python notebook file.
7. List of dependencies can be installed using :
	'sudo python3 -m pip install -r requirements.txt'
8. The model is saved as 'my_model_scaled_3'
