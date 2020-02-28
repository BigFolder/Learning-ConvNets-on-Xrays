# Learning-ConvNets-on-Xrays
Using Tensorflow I try my best to really begin understanding Convolutional Neural Networks. OVerall this has been a fantastic learning experience. There is a lot that goes into just working with the dataset, simply trying to get the images ready to be fed into the model.

I used the Chest-XRay dataset from Kaggle that can be found here https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia 
The Dataset is pretty large it's got A LOT of images and the download is a couple GB so I am unable to add it to github as of right now.

My goal was to see if I could create a Convnet that could predict whether an image of an Xray of a chest was Normal or Had Pneumonia.
Overall I was successful in actually creating the model and having it predict, but the most successful I got to was only 80%, I started to notice that making any changes to the complexity of the model added on substantially more time to the Fitting of my NN ( Since none of my computers are NVidia I am incapable of utilizing Tensorflow GPU at this time).

I still return to this on the weekends when I want to brush up on my understanding on something involving Convnets. The power, easy accessibility and readability of Jupyter notebooks cannot be undersold.
