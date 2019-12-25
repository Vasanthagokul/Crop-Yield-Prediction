   Before u think that this is legit project. This was one of the projects I had worked on during and month long internship. This is my first time having a hands on experience with a datascience project and also a hands on experience with creating neural networks which I could'nt make head or tails of before this. 

# Crop-Yield-Prediction

#### Dataset:
  There are 2 datasets. One has been obtained from the public govrnment of india website and includes pretty much every state in india, it has over 250K entries. The other dataset is a similar dataset but it has a lot more features like precipitation and humidity values.
  
#### PreProcessing:
  I preprocessed the datasets by one hot encoding all the categorical data. Substituting the mean in records for missing data. 
								-There re 3 columns in the second dataset that are not needed as they increase the error rate of the models.
								-The columns are 'State', 'County' and 'precipTypeIsOther'
								-I did not know how to preprocess the date column so I decided to leave it out.(This could also be included in future)
I spilt train and test as 70/30.

#### Algorithms:
  I used random forest, polynomial support vector machine and also XGB regression which I think is a variation of random forest regression.
	
#### Neural Network:
  This is the first time working with neural networks so I designed a very simple neural network which 1 input and 1 output layer and 3 hidden layers.(all of them were dense layers)
	
#### Conclusions:
##### Dataset1:
  
