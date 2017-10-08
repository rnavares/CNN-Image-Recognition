[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Keras Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Overview

This project shows how to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images.  Given an image of a dog, ther algorithm will identify an estimate of the canine’s breed.  If supplied an image of a human, the code will identify the resembling dog breed.  

![Sample Output][image1]


## Project Instructions

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/rnavares/dog-project.git
		cd dog-project
	```
2. Download the [dog dataset].  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`. 
3. Download the [human dataset].  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  

4. Donwload the [VGG-16 bottleneck features].  Place it in the repo, at location `path/to/dog-project/bottleneck_features`.

5. Obtain the necessary Python packages, and switch Keras backend to Tensorflow.  
	
6. Open the notebook and follow the instructions.
	
	```
		jupyter notebook dog_app.ipynb
	```


