[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


# Dog breed classification project

This is the repository of my capstone project for the Udacity Machine Learning engineer nanodegree. The code was developed in the dog_app jupyter notebook and the models was trained in a workspace provided by Udacity. 

The main goal is to build an algorithm that takes an image path and if it’s a human image, it will predict the resembling dog breed. If there is a dog in the image, it will predict its breed.

## Dataset

[Dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)

[Faces dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip)


## Steps

- 1. Exploratory data analysis.
- 2. Built a face detector with a haar cascade classifier.
- 3. Built a dog detector with a VGG-16 pre-trained model.
- 4. Create a CNN model from scratch, train it and test it.
- 5. Use transfer learning with VGG-16 model. Train and test it.
- 6. Built a final algorithm whith the human detector, dog detector and the last transfer learning model.




