# Multi-Label-Prediction-For-videos-using-Zero_Shot_Learning


## The dataset: 
UCF-101 Action Dataset from the link I mentioned in the ipython file. That will directly download the dataset to the storage. 
## Feature extractor: 
3D-CNN trained on sports 1-M dataset .so I used these trained weights to extract the video feature of UCF-101 dataset.
## Dimension Reduction: 
created a simple Nural network to reduce the dimensions of the features from 4096 to 1024 Dimensional vector.
## Feature embedding: 
Trained the feature vectors into the model to get semantic feature vectors.
## Feature plotting: 
Used Tensorboard projector to plot feature vectors into the semantic space and where we can use PCA and t-sne algorithms to classify the values.
## Label prediction: 
Used my own lines of codes to predict the labels by using the feature vectors and label word vectors.



