# LLM_detect_AI
In recent years, large language models (LLMs) have become increasingly sophisticated, capable of generating text that is difficult to distinguish from human-written text. This code develops a model that can detect whether a paper was written by a student or a master's degree in law.

# Hardware and Software
Kaggle default environment

# Datasets
We used 5 datasets as the training set, with only 3 files in the datasets. The links to the other two files are https://www.kaggle.com/datasets/kagglemini/train-00000-of-00001-f9daec1515e5c4b9 and https://www.kaggle.com/datasets/thedrcat/daigt-v2-train-dataset

# Train and Test
The operations on the training set and test set data are both in the tokenizer_data.py file. If you want to predict new data, you can modify the path of the test in the prepare_data.py file to the file path where you need to predict the data. The training and prediction of the final model are both in the train_predict.py file.
