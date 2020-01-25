# In this project we will make a image captioning bot
## The dataset used in this project is the flickr8k dataset which can be downloaded from [here](https://www.kaggle.com/shadabhussain/flickr8k)

* The word embeddings layer was not trained and the weights were initialized from the [glove 6B 50D embedding](https://www.kaggle.com/rdizzl3/glove6b50d)
* The images were first passed through a pretrained RESNET50 model to extract features out of the images. These features are then passed as an input to the model. The embeddings are saved in a pickle object and can be easily loaded
* Note that the training was done on Google colab due to large number of trainable parameters. The saved model can be found in the model_weight directory.