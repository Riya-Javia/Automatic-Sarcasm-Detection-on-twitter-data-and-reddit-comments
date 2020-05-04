# Automatic-Sarcasm-Detection-on-twitter-data-and-reddit-comments
AUTOMATIC SARCASM DETECTION

The project aims at sarcasm classification on the twitter data and the reddit comments data.

There have been two datasets used in the project
1) Twitter dataset(Ghosh)
2) Reddit comments dataset (Khodak)

**Folders**
1) Twitter_dataset_Ghosh  
  i) Codes - Contains 3 notbook .ipynb files   
  ii)Resources - Contains all the raw and the preprocessed data and the outputs at intermediate states 

**2) Reddit_dataset_Khodak**	
The main SARC(khodak)  dataset has not been uploaded due to its size.    
It can be downloaded from https://www.kaggle.com/danofer/sarcasm and trained balance sarcasm,csv has been used     
The content of the reddit dataset has been split into different folders due to its dataset size  
i)reddit_train has the preprocessed trained dataset  
ii)reddit_test has the preprocessed trained dataset  
iii)Reddit_codes has the 2 notebook .ipynb files   

**3)Sentiment**
i)Codes - Contains 1 notebook .ipynb file   
ii)Resources - It contains raw as well as preprocessed dataset  
	

**Dependencies to run the project**
1) Sentistrength tool
2) nltk 
3) Keras
4) Tensorflow
5) numpy
6) scipy
7) gensim
8) sklearn
9) seaborn
10) matplotlib
11) pandas
12) pickle


For running the codes, there might be requierement for changing the file paths.

**Flow for the Ghosh dataset**

1) The raw data has been preprocessed using the twitter_preprocessing file. In the intermediate step the sentistrength tool has to be used for the training and testing data to get the polarites.  
2) The embedding_features.ipynb is used to get all the embedding features from the dataset. This step would take a considerate amount of time.  
3) The twitter_dataset.ipynb file has all the models used in the project for Ghosh dataset.   

**Flow for the Khodak dataset**

1) The raw data has been preprocessed using the reddit_preprocessing file.  
2) The sentiment.ipynb file from the sentiment folder is used to generate a sentiment model which is used as a pre trained model in the latter phase of reddit dataset project.  
3) The reddit_dataset.ipynb file contains all the models used for the classification of the SARC dataset.  
