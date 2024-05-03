## Project Overview

### Part-1
The dataset “cnn_dataset.zip” consists of three folders – dogs, food, and vehicles. Each class consists of 10,000 RGB 
images of size 64x64 pixels. So, there are a total of 30,000 images. The mean of the dataset is [0.5047, 0.4501, 0.3840] 
and standard deviation is [0.2386, 0.2384, 0.2404]. We have three values each because we have 3 channels for the 
images.

We implement AlexNet CNN in pytorch, modifying only the input and output layers of the model as the original AlexNet 
accepts 224x224 sized images and outputs 1000 classes. As discussed, our images are of size 64x64 and we need only 
three output classes. We split the dataset into 80% train set and 20% test set. We have used Cross Entropy Loss as the 
loss function, Adam optimizer and trained the CNN for 20 epochs.

### Part-2

The dataset we use for this part of the project is Google Street View House Number (SVHN) data. It consists of two 
folders – train and test. The train folder consists of 73,257 RGB 32x32 images and the test folder consists of 26,032 
images. The mean of the train set is [-0.0776, -0.0729, -0.0646] and the standard deviation is [1.0674, 1.0480, 1.0278]. 
We have three values each as the images have 3 channels.

We optimize the CNN (from Part-1) and use a number of data augmentation techniques to increase the performance of the model.
