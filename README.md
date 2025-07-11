Just the code for a self trained Image Captioning Model.
Used Pytorch and self implemented the VGG16-based CNN to extract image features and connected it to an LSTM to generate tokens from the features. The tokens are then used to generate the captions. 
The Model is not pre-trained and the Flickr8k dataset was used to train the model. Due to PC limitations, the training was not completed so the performance can't be verified.
