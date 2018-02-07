### Semantic Segmentation Project ###

Submitted by - Vishal Rangras

#### Semantic Segmentation of road images to identify road pixels using Fully Convolutional Network trained on a pretrained VGG16 model ####

The goals for this project are to:

1. Load a pretrained VGG16 model and extract its input_image layer, Vgg Layer 3, 4 and 7 output
2. Implement Encoder and Decode in VGG16 model using Fully Convolutional Network, Upsampling and Skip connection.
3. Implement Neural network loss and optimizer for training. 
4. Train the model on training data using reasonable hyperparameters.
5. Run inference on test data after the model is trained for semantic segmentation.

**[Rubric](https://review.udacity.com/#!/rubrics/989/view) Points**

### Results ###

[image1]: ./img/001.png "Training 1"

[image2]: ./img/002.png "Training 2"

[image3]: ./img/003.png "Result 1"

[image4]: ./img/004.png "Result 2"

[image5]: ./img/005.png "Result 3"

[image6]: ./img/006.png "Result 4"

<h3 align="center"> Training Logs <h3>

![alt text][image1]

![alt text][image2]

<h3 align="center"> Output images <h3>

![alt text][image3]

![alt text][image4]

![alt text][image5]

![alt text][image6]

### Dependencies ###
##### Frameworks and Packages #####

 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)

##### Dataset #####

The [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) is downloaded from [here](http://www.cvlibs.net/download.php?file=data_road.zip) and used for training.  

##### Run #####

Run the following command to run the project:

```
python main.py
```

**Note** If running this in Jupyter Notebook system messages, such as those regarding test status, may appear in the terminal rather than the notebook.

### Submission ###

1. All the tests were passed.
2. Following files are submitted as part of submission.
 - `helper.py`
 - `main.py`
 - `project_tests.py`
 - Newest inference images from `runs` folder  (**all images from the most recent run**)
 
