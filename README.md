# Natural Language Processing with Disaster Tweets
## Predict which Tweets are about real disasters and which ones are not
This repository is for the final semester project in the Intelligent Data Analysis and Machine Learning 2 course, in the master of Cognitive Systems programme of Potsdam University.

This project is based on the Kaggle Competition: Natural Language Processing with Disaster Tweets, where a tweet should be categorized as either containing terms refering to real disasters or not.

The competition gives an acess to a dataset of 10,000 tweets that were hand classified. The dataset was created by the company figure-eight and originally shared on their ‘Data For Everyone’ website.

Tweet source: https://twitter.com/AnyOtherAnnaK/status/629195955506708480

The repository includes:
- Data description: a file that includes a short description of the data structure
- Dataset: the annotated dataset taken from the Kaggle website 

- Project: a Google Colaboratory file with includes the whole project and needs a notebook enviroment to be run.


## Project file:
This file includes the follwing: 
- Text preprocessing: text cleaning, toknazation, adding GloVe embeddings 
- Models : with a simple feedfarward neural network as a baseline model, compared to an LSTM and CNN models for text classifocation.
- Evaluation : F1 score and accuracy visualization graphs for each of teh models 


