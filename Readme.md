# Team5-Multiverse
Multiverse project from m2pi 2023: Analyzing deforestation in the Amazon Basin with Deep learning.

We use as a base model ResNet50 fine-tuned on the Amazon dataset from Kaggle. We then tensorize the fully connected layer of the base model into different shapes, and retrain it on the same dataset. We record the performance and complexity of each of the models corresponding to the different tensorization shapes. See the final presentation for a sneak peek into the results we got. 

Until now we only did tensorize the fully connected layer, we plan to tensorize the convolutional layers as well. 

The training data can be downloaded from https://www.kaggle.com/competitions/planet-understanding-the-amazon-from-space/data?select=train-jpg
