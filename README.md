# Hindi_Fake_News_Detection

Anlysing performance of Bag-of-Word related features over Hindi Language for Fake News detections. Sequential Models like LSTM and BERT is developed for fake news detection for Hindi Language.				

## Instructions: 

Requirements: Install all the required dependencies mentioned in requirement.txt file. <br/>
Dataset: Save all the data set(csv files) in a folder named "final-datasets" in the same folder.


To run BERT Model:

	1. Install the dependencies provided in the requirement file. 
	2. Go to current directory and excute ```python BERT.py``` command.

	After execution: 

	1. Enter the name of the dataset for which you want to run the model for. first for train then for test. eg, "bbc_ner_train.csv".
	2. After feature extraction, model training and prediction, accuracy, class wise F-score and macro-average will be printed on the terminal.

To run LSTM Model:

	Following are the instruction needed to be followed on all the datasets

	1. Install the dependencies provided in the requirement file.
	2. Go to current directory and excute ```python LSTM.py``` command.
   	 
	After Execution: 

	1. Enter the name of the dataset for which you want to run the model for. first for train then for test. eg, "bbc_ner_train.csv".
	2. Trained model will be generated.
