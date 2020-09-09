# The-Identification-of-pill-images-using-CNN-VGG16
![Picture3](https://user-images.githubusercontent.com/70999601/92566370-52734380-f2a6-11ea-86be-aa2d294c78f2.jpg)
### In this project , studies and techniques are used. Convolutional Neural Network and Transfer learning In order to test how the technique can classify tablets by using Transfer learning 3 models  VGG16, Inception-Resnet-V2 and Xception are used as a training model and constructing a Convolutional Neural Network to connect at the end of each Transfer learning model. There are 28 types of tablets and capsules, divided into 2,760 images train data sets and 2 test data sets. The first test data set contains 230 images. The second test data set contains 84 images. Test data set 2 is an image taken from actual use. All 3 models gave 100% accuracy of the test data set in test 1, all 3 models and 71.42%, 82.14% and 77.38% accuracy of the test data set 2.  Respectively.

## Step in Project
1. Collect data training data and the test data, we used 3,074 image data, including tablets and capsules, with different characteristics.
2. Preprocessing 	: In preprocessing, we will divide it into 2 steps which are Create Bounding Box and crop and Data Augmentation 
3. Classificatio : 3 model VGG16 , InceptionResnetV2 , Xception


