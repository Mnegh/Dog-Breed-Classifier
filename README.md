
## Project Overview

In this project, Convolutional Neural Networks (CNNs) will be used to correctly identify different breeds of dogs in an image. It will involve training a CNN from scratch and using transfer learning to greatly boost the performance of the model.

* If the model detects a dog in the image, it will predict its breed. 
* If the model detects a human in the image, it will output the resembling breed.
* If it has neither a dog or a human, it will ask for another image.

## File Descriptions

`dog_app.ipynb` contains the code that was used in project.

`bottleneck_features` will contain the files that will extract the featuers using a pretrained network.

`haarcascades` contains the files needed for the face detection algorithm.

`requirements` will have the needed libraries.

`report.pdf` contains the findings of this project.

## Project Results

The final model has acheived an accuracy of 83.97%, that classifies breeds effectively.

### Instructions

1. Clone the repository and navigate to the downloaded folder.
```	
git clone https://github.com/Mnegh/Dog-Breed-Classifier
```

2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`. 

3. Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 

4. Donwload the [VGG-16 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz) for the dog dataset.  Place it in the repo, at location `path/to/dog-project/bottleneck_features`.

5. Downlaod the needed libraries:
* Sklearn
* Numpy
* Glob
* Matplotlib
* Tensorflow and Keras
* cv2

