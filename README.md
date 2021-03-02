# Georgy_recognition
***
_This project is classification St. George on image._
<br>In this project, a convolutional neural network was built, capable of recognizing the presence or absence of St. George in the image with an accuracy of ~ 78%.
***
## What do you need for repeat this project?
_You need install:_
* `python = "^3.7"`
* `jupyter = "^1.0.0"`
* `matplotlib = "3.3.2"`
* `numpy = "1.19.2"`
* `tensorflow = "2.1.0"`
* `requests = "2.25.1"`
* `pandas = "1.1.2"`
<br>__OR__
<br>_Use [Poetry](https://python-poetry.org/docs/cli/#install)_
***
## Repeat: Step by step
* Step 1: Download images from csv file
* * Run [Download images notebook](https://github.com/DMBabich/Georgy_recognition/blob/main/Download_images.ipynb)
* * When you do this, the notebook will create 2 folders: <br>`yes` _(all 2681 images with George)_ and `no` _(all 3366 images without George)._
* Step 2: Clear dataset
* * In the `yes` folder, you need to delete _bad images_ (real people, castle, etc.)
* * After cleaning I have 2259 images in `yes` folder
* Step 3: Split images
* * Run [Split images notebook](https://github.com/DMBabich/Georgy_recognition/blob/main/Split_images.ipynb)
* * When you start this notebook, all data will be split at `70% / 30%`. _This is required to create a training and test dataset._
* * Will created 2 folder: `train` _(for train dataset)_ and `test` _(for test dataset)_
* Step 4: Learn CNN model
* * Run [Softmax model copy](https://github.com/DMBabich/Georgy_recognition/blob/main/Softmax_model-Copy1.ipynb)
* * On this step, we create and train convolutional neural network. We use `datagen` because have small data. <br>After train model, we __plot accuracy and loss__.
<br>![smooth accuracy](https://github.com/DMBabich/Georgy_recognition/blob/main/plot_img/smooth-Model_softmax-accuracy.png)
<br>![smooth loss](https://github.com/DMBabich/Georgy_recognition/blob/main/plot_img/smooth-Model_softmax-loss.png)
* Step 5: Check model
* * Run [Example notebook](https://github.com/DMBabich/Georgy_recognition/blob/main/Examples.ipynb)
* * In this notebook, we test our model with our data. We are using images from the `example` folder. <br>Notebook uses class predictions. The forecast value will be printed in the last cell
Finally, after all the steps, you will have the following structure:
<br>![after all steps](https://github.com/DMBabich/Georgy_recognition/blob/main/plot_img/after_all_steps.jpg)
***
## Links
+ [Poetry](https://python-poetry.org/docs/cli/)
+ [My compiled and trained model](https://drive.google.com/drive/folders/1NFOEC5Zpuu3izriM83Max26_ws3JoVs5?usp=sharing)
+ [Task](https://enterideas.com/testcv)
