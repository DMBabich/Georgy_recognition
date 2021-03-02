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
* * aaa
* Step 4: Learn CNN model
* * aaa
* Step 5: Check model
* * aaa
